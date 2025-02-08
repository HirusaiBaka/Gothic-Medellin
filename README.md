<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gothic Medellín</title>
    <link href="https://fonts.googleapis.com/css2?family=Georgia&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Luminari&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #000000;
            color: #FFFFFF;
            font-family: 'Georgia', serif;
        }
        h1, h2, h3 {
            font-family: 'Luminari', cursive;
            color: #C0C0C0;
        }
        h1 { font-size: 48px; }
        h2 { font-size: 36px; }
        h3 { font-size: 24px; }
        .hero {
            background: url('medellin-night.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }
        .hero::before {
            content: "";
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(to bottom, #000000, transparent);
        }
        .hero h1 {
            position: relative;
            z-index: 1;
        }
        .cta {
            background-color: #8B0000;
            padding: 10px 20px;
            font-size: 18px;
            font-family: 'Luminari', cursive;
            color: #000000;
            border: none;
            cursor: pointer;
        }
        .cta:hover {
            background-color: #722F37;
        }
        .section {
            padding: 50px;
            background-color: #1A1A1A;
            margin-bottom: 20px;
            text-align: center;
        }
        .gallery img {
            width: 30%;
            margin: 10px;
            border: 2px solid #8B0000;
        }
        .video-container, .audio-container {
            text-align: center;
            margin-top: 20px;
        }
        iframe {
            width: 80%;
            height: 400px;
            border: none;
        }
        .interactive-map {
            margin: 20px auto;
            text-align: center;
        }
        .footer {
            background-color: #1A1A1A;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gothic Medellín</h1>
        <nav>
            <ul>
                <li><a href="#el-poblado">El Poblado</a></li>
                <li><a href="#universidad">Universidad de Antioquia</a></li>
                <li><a href="#comuna-13">Comuna 13</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <h1>Discover Medellín's Dark Beauty</h1>
        <button class="cta">Begin Your Journey</button>
    </section>
    
    <section id="el-poblado" class="section">
        <h2>El Poblado: The Luxurious Heart of Darkness</h2>
        <p>El Poblado is known for its upscale atmosphere, high-end restaurants, and vibrant nightlife, but beneath its glamorous exterior lies an air of mystery. Gothic-inspired cafes and dimly lit bars offer a haunting charm that entices night wanderers and seekers of the unknown.</p>
        <div class="gallery">
            <img src="el_poblado_1.jpg" alt="El Poblado at night">
            <img src="el_poblado_2.jpg" alt="Gothic architecture in El Poblado">
        </div>
        <div class="audio-container">
            <audio controls>
                <source src="el_poblado_audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
    </section>
    
    <section id="universidad" class="section">
        <h2>Universidad de Antioquia: Halls of Knowledge and Whispers of the Past</h2>
        <p>One of the oldest universities in Colombia, the Universidad de Antioquia is shrouded in legends and intellectual mysteries. Its historic buildings, cloisters, and hidden courtyards serve as a backdrop to stories of scholars, revolutions, and ghostly encounters.</p>
        <div class="video-container">
            <iframe src="https://www.youtube.com/embed/your_video_id"></iframe>
        </div>
    </section>
    
    <section id="comuna-13" class="section">
        <h2>Comuna 13: From Shadows to Vibrant Rebirth</h2>
        <p>Once one of Medellín’s most dangerous areas, Comuna 13 has undergone a stunning transformation. The streets, covered in vivid murals, tell stories of struggle and resilience. At night, the alleyways hold onto an eerie yet mesmerizing beauty, where art and history merge to create an unforgettable experience.</p>
        <div class="gallery">
            <img src="comuna_13_1.jpg" alt="Street art in Comuna 13">
            <img src="comuna_13_2.jpg" alt="View of Comuna 13">
        </div>
        <div class="interactive-map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1dxyz"></iframe>
        </div>
    </section>
    
    <footer class="footer">
        <p>&copy; 2025 Gothic Medellín. All rights reserved.</p>
    </footer>
</body>
</html>
