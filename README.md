# IGNOU-ASSIGNMENT-SOLUTIONS-
यहाँ पर सभी IGNOU कोर्स का सॉल्व assignment पेपर मिलता है। वो भी बहुत कम खर्च में ।
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Manoj Digital Store</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.card {
    background: white;
    width: 350px;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

h1 {
    margin: 15px 0 5px;
}

.price {
    font-size: 22px;
    color: green;
    margin: 10px 0;
}

button {
    width: 100%;
    padding: 12px;
    border: none;
    background: #667eea;
    color: white;
    font-size: 18px;
    border-radius: 8px;
    cursor: pointer;
}

button:hover {
    background: #5a67d8;
}

.small-text {
    font-size: 12px;
    color: gray;
    margin-top: 10px;
}
</style>
</head>

<body>

<div class="card">
    <img src="https://via.placeholder.com/350x200" alt="PDF Cover">

    <h1>Facebook Growth Master Guide</h1>
    <p>Step-by-step strategy to grow fast in 2026.</p>

    <div class="price">₹99 Only</div>

    <button onclick="buyNow()">Buy Now</button>

    <p class="small-text">
        Secure Payment | Instant Download
    </p>
</div>

<script>
function buyNow() {
    window.location.href = "https://YOUR_PAYMENT_LINK_HERE";
}
</script>

</body>
</html>
