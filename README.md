<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ambulance Dispatch System</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f5f8fa;
        color: #333;
        margin: 0;
        padding: 0;
    }
    header {
        background-color: #e53935;
        color: white;
        padding: 20px;
        text-align: center;
    }
    h1 {
        margin: 0;
    }
    main {
        max-width: 900px;
        margin: auto;
        padding: 20px;
    }
    section {
        background: white;
        margin-bottom: 20px;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    h2 {
        color: #e53935;
    }
    ul {
        line-height: 1.6;
    }
    footer {
        text-align: center;
        padding: 15px;
        background-color: #e53935;
        color: white;
        margin-top: 20px;
    }
</style>
</head>
<body>

<header>
    <h1>🚑 Ambulance Dispatch System</h1>
    <p>Real-time emergency ambulance allocation with live traffic & routing</p>
</header>

<main>

<section>
    <h2>📌 Overview</h2>
    <p>
        The <strong>Ambulance Dispatch System</strong> is designed to ensure fast and efficient emergency response by automatically 
        assigning the nearest available ambulance to a patient using real-time traffic data from Google Maps.
    </p>
</section>

<section>
    <h2>⚙️ How It Works</h2>
    <ol>
        <li>🚨 <strong>Request:</strong> Patient requests an ambulance directly or an admin enters their details.</li>
        <li>📍 <strong>Find Ambulance:</strong> System finds the closest ambulance using live traffic data (Google Maps API).</li>
        <li>🏥 <strong>Find Hospital:</strong> Nearest hospital is located based on patient’s position.</li>
        <li>🗺 <strong>Route Map:</strong> Real-time route (Ambulance → Patient → Hospital) is generated using Folium.</li>
        <li>🚘 <strong>Driver Dashboard:</strong> Drivers log in to view assigned jobs & maps.</li>
        <li>📊 <strong>Admin Dashboard:</strong> Admin can monitor all dispatches and assign new ones.</li>
    </ol>
</section>

<section>
    <h2>💡 Key Features</h2>
    <ul>
        <li>Real-time traffic-based ambulance selection</li>
        <li>Automatic hospital selection</li>
        <li>Interactive route map generation with Folium</li>
        <li>Separate driver & admin portals</li>
        <li>Live tracking of ambulance location</li>
    </ul>
</section>

<section>
    <h2>🛠 Tech Stack</h2>
    <ul>
        <li>Python (Flask/Django backend)</li>
        <li>Google Maps API (Traffic & Distance Matrix)</li>
        <li>Folium (Map visualization)</li>
        <li>HTML, CSS, JavaScript (Frontend)</li>
        <li>SQLite/MySQL (Database)</li>
    </ul>
</section>

</main>

<footer>
    <p>© 2025 Ambulance Dispatch System | Developed with ❤️ for faster emergency response</p>
</footer>

</body>
</html>
