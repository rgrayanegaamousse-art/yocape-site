# yocape-site 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yocap - Buy Skull Caps</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-dark text-white py-3">
        <div class="container">
            <h1 class="h3">Yocap</h1>
            <p class="mb-0">Premium Skull Caps - Reliable and Affordable</p>
        </div>
    </header>

    <main class="container my-5">
        <section id="product" class="row">
            <div class="col-md-6">
                <img src="https://via.placeholder.com/400x400?text=Skull+Cap" alt="Skull Cap" class="img-fluid rounded">
            </div>
            <div class="col-md-6">
                <h2>Skull Cap</h2>
                <p>High-quality, comfortable skull caps made from premium materials. Perfect for any season.</p>
                <div class="mb-3">
                    <label for="quantity" class="form-label">Quantity:</label>
                    <select id="quantity" class="form-select">
                        <option value="1">1 Piece - 70 DH</option>
                        <option value="2">2 Pieces - 135 DH</option>
                        <option value="3">3 Pieces - 180 DH</option>
                    </select>
                </div>
                <button id="add-to-cart" class="btn btn-primary">Add to Cart</button>
            </div>
        </section>

        <section id="cart" class="mt-5" style="display: none;">
            <h3>Your Cart</h3>
            <ul id="cart-items" class="list-group mb-3"></ul>
            <p>Total: <span id="total">0</span> DH</p>
            <button id="checkout-btn" class="btn btn-success">Proceed to Checkout</button>
        </section>

        <section id="checkout" class="mt-5" style="display: none;">
            <h3>Checkout</h3>
            <form id="checkout-form">
                <div class="mb-3">
                    <label for="name" class="form-label">Full Name</label>
                    <input type="text" id="name" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" id="email" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label for="address" class="form-label">Shipping Address</label>
                    <textarea id="address" class="form-control" required></textarea>
                </div>
                <button type="submit" class="btn btn-success">Complete Purchase</button>
            </form>
        </section>
    </main>

    <footer class="bg-dark text-white py-3 text-center">
        <p>&copy; 2023 Yocap. All rights reserved. Secure payments and fast shipping.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
