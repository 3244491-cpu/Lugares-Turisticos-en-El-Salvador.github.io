https://app.netlify.com/drop

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafeterías de Hazel Cedillos</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff5f0;
        }
        header {
            background-color: #ff8c94;
            color: white;
            padding: 25px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2.2em;
        }
        .cafeteria-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 25px;
        }
        .cafeteria {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            width: 300px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }
        .cafeteria:hover {
            transform: translateY(-5px);
        }
        .cafeteria img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .cafeteria h2 {
            margin: 10px 0;
            color: #ff5e78;
        }
        .cafeteria p {
            padding: 0 15px 15px 15px;
            color: #555;
        }
        .cafeteria a {
            display: inline-block;
            margin-bottom: 15px;
            padding: 8px 15px;
            background-color: #ff5e78;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            transition: background-color 0.3s;
        }
        .cafeteria a:hover {
            background-color: #ff3b55;
        }
        footer {
            background-color: #ff8c94;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cafeterías de Hazel Cedillos</h1>
        <p>Los mejores lugares para disfrutar un buen café en la ciudad</p>
    </header>

    <div class="cafeteria-container">
        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Cafetería Aroma">
            <h2>Cafetería Aroma</h2>
            <p>Ubicada en el centro de la ciudad, Aroma ofrece cafés artesanales y un ambiente acogedor.</p>
            <p><strong>Dirección:</strong> Calle Central 123</p>
            <a href="https://goo.gl/maps/Xd5qGvFz9Qv4n3fD6" target="_blank">Ver en Google Maps</a>
        </div>

        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f" alt="Café del Sol">
            <h2>Café del Sol</h2>
            <p>Disfruta de cafés orgánicos y pastelería fresca en un espacio lleno de luz y tranquilidad.</p>
            <p><strong>Dirección:</strong> Av. Reforma 45</p>
            <a href="https://goo.gl/maps/3RrXY8cQpRqXqkFg7" target="_blank">Ver en Google Maps</a>
        </div>

        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348" alt="La Taza Mágica">
            <h2>La Taza Mágica</h2>
            <p>Especialidad en cafés de origen y bebidas innovadoras para los amantes del café.</p>
            <p><strong>Dirección:</strong> Plaza Las Flores 7</p>
            <a href="https://goo.gl/maps/5kT6Kv3W3XvXnXyF7" target="_blank">Ver en Google Maps</a>
        </div>

        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1529042410759-befb1204b468" alt="Café Luna">
            <h2>Café Luna</h2>
            <p>Un espacio íntimo para leer y disfrutar de cafés especiales acompañados de postres caseros.</p>
            <p><strong>Dirección:</strong> Barrio Santa Elena 12</p>
            <a href="https://goo.gl/maps/Q2HcD7wR2XK2" target="_blank">Ver en Google Maps</a>
        </div>

        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1506086679527-0c35a8c91f47" alt="Café Aroma Verde">
            <h2>Café Aroma Verde</h2>
            <p>Destaca por su café orgánico y su compromiso con el medio ambiente y productores locales.</p>
            <p><strong>Dirección:</strong> Av. La Libertad 89</p>
            <a href="https://goo.gl/maps/L3RkH5JpJvK2" target="_blank">Ver en Google Maps</a>
        </div>

        <div class="cafeteria">
            <img src="https://images.unsplash.com/photo-1510626176961-4b8a6d7f36c1" alt="Café Central">
            <h2>Café Central</h2>
            <p>Ubicado en el corazón de la ciudad, perfecto para reuniones y disfrutar de cafés clásicos y modernos.</p>
            <p><strong>Dirección:</strong> Centro Histórico 10</p>
            <a href="https://goo.gl/maps/JmT9R7hU8g92" target="_blank">Ver en Google Maps</a>
        </div>
    </div>

    <footer>
        <p>Hazel Cedillos &copy; 2025 - Proyecto de Clase</p>
    </footer>
</body>
</html>
