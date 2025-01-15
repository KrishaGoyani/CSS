https://github.com/Anuj-Kumar-Sharma/Web-Development-Course/tree/master/learncss/12.%20flex%20complete%20landing%20page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cleaning Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section class="services">
        <div class="service-card">
            <img src="https://via.placeholder.com/300x200" alt="Booking Image">
            <h2>Book a Clean Online = Anytime, Anywhere</h2>
            <p>
                Whether you need certain rooms done or the entire house deep cleaned, The Maids has a clean 
                to fit your needs and budget. Find The Maids near you, get a free quote and book your service 
                online 24/7. Pick your package, select your day and preferred time, book your clean.
            </p>
        </div>
        <div class="service-card">
            <img src="https://via.placeholder.com/300x200" alt="Trained Team">
            <h2>Trained Teams = Faster Cleans</h2>
            <p>
                Flexible team sizes to meet your needs. Our teams can get in and out of your home faster 
                with a more thorough clean. The only maid service backed by Mr. Clean®, our highly trained 
                teams are bonded, insured, and right around the corner.
            </p>
        </div>
        <div class="service-card">
            <img src="https://via.placeholder.com/300x200" alt="Custom Clean">
            <h2>Your Custom Cleans = Affordable Routine</h2>
            <p>
                Our 22-Step Cleaning Process cleans your home top to bottom and guards against germs and 
                allergens. We treat your home like it’s our own. It’s more than a job to us — it’s our calling.
            </p>
        </div>
    </section>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8fcff;
}

.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.service-card {
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 300px;
    padding: 20px;
}

.service-card img {
    width: 100%;
    border-radius: 10px 10px 0 0;
}

.service-card h2 {
    color: #0066cc;
    font-size: 18px;
    margin: 15px 0;
}

.service-card p {
    color: #555555;
    font-size: 14px;
    line-height: 1.6;
}
