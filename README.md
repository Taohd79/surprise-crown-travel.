<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise Crown Travel and Tours</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        header { background-color: #ffcc00; padding: 20px; text-align: center; }
        nav ul { list-style: none; padding: 0; display: flex; justify-content: center; background: #333; }
        nav ul li { margin: 0 15px; }
        nav ul li a { color: white; text-decoration: none; }
        section { padding: 20px; text-align: center; }
        .deal-card { background: white; margin: 20px auto; padding: 15px; border-radius: 10px; width: 300px; }
        footer { background: #333; color: white; text-align: center; padding: 10px; }
    </style>
    <script>
        function exploreDeals() { alert('Explore amazing travel deals!'); }
    </script>
</head>
<body>
    <header>
        <h1>Surprise Crown Travel and Tours Nigeria Limited</h1>
        <p>Your Gateway to the Cheapest Airfares Worldwide!</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#flights">Book Flights</a></li>
            <li><a href="#deals">Special Deals</a></li>
            <li><a href="#destinations">Top Destinations</a></li>
            <li><a href="#blog">Travel Blog</a></li>
            <li><a href="#dashboard">User Dashboard</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>
    
    <section id="home">
        <h2>Welcome to Surprise Crown Travel and Tours</h2>
        <p>Book your next adventure with confidence. Compare real-time airfares and get the best deals!</p>
        <button onclick="exploreDeals()">Explore Deals</button>
    </section>
    
    <section id="flights">
        <h2>Search and Book Your Flight</h2>
        <form>
            <label for="from">From:</label>
            <input type="text" id="from" name="from" placeholder="Enter departure city" required>
            <label for="to">To:</label>
            <input type="text" id="to" name="to" placeholder="Enter destination" required>
            <label for="date">Departure Date:</label>
            <input type="date" id="date" name="date" required>
            <label for="return">Return Date:</label>
            <input type="date" id="return" name="return">
            <button type="submit">Search Flights</button>
        </form>
    </section>
    
    <section id="deals">
        <h2>Exclusive Travel Deals</h2>
        <div class="deal-card">
            <h3>Dubai Getaway - 40% Off</h3>
            <p>Fly from Lagos to Dubai at unbeatable prices.</p>
            <button>Book Now</button>
        </div>
        <div class="deal-card">
            <h3>London Special - 30% Off</h3>
            <p>Affordable flights from Abuja to London.</p>
            <button>Book Now</button>
        </div>
    </section>
    
    <footer>
        <p>Email: info@surprisecrowntravel.com | Phone: +234 800 123 4567</p>
        <p>Follow us: <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a></p>
        <p>&copy; 2025 Surprise Crown Travel and Tours Nigeria Limited. All rights reserved.</p>
    </footer>
</body>
</html>
