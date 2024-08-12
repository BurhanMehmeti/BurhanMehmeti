<!DOCTYPE html>
<html lang="sq">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoSallon Malti</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />
    <script src="script.js" defer></script>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <div class="container">
        <h1>AutoSallon Malti</h1>
        <nav>
            <ul>
                <li><a href="#home">Kreu</a></li>
                <li><a href="#featured">Automjetet e Veçanta</a></li>
                <li><a href="#services">Shërbimet</a></li>
                <li><a href="#testimonials">Dëshmitë</a></li>
                <li><a href="#contact">Kontakti</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="home" class="hero">
    <div class="hero-content">
        <h2>Gjeni Automjetin Tuaj të Ëndrrave</h2>
        <p>Zbuloni automjetin ideal për ju nga koleksioni ynë i gjerë të automjeteve të reja dhe të përdorura.</p>
        <a href="#featured" class="btn btn-primary">Shikoni Automjetet Tona</a>
    </div>
</section>

<section id="featured" class="featured-cars">
    <div class="container">
        <h2>Automjetet e Veçanta</h2>
        <div class="car-list">
            <div class="car">
                <img src="../Projekti Burhani/GLE 350D .JPG" alt="Modeli i Automjetit 1">
                <div class="car-details">
                    <h3>Volkswagen Golf 8</h3>
                    <p>Çmimi: £28,000</p>
                    <p>Motori: 1.0 eTSI</p>
                    <a href="#contact" class="btn btn-secondary">Na Kontaktoni</a>
                </div>
            </div>
            <div class="car">
                <img src="car2.jpg" alt="Modeli i Automjetit 2">
                <div class="car-details">
                    <h3>Mercedes-Benz E 220 d 4MATIC 9G-Tronic</h3>
                    <p>Çmimi: £65,000</p>
                    <p>Motori: 2.0 I4</p>
                    <a href="#contact" class="btn btn-secondary">Na Kontaktoni</a>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="services" class="services">
    <div class="container">
        <h2>Shërbimet Tona</h2>
        <div class="service-list">
            <div class="service">
                <i class="fa fa-dollar-sign"></i>
                <h3>Financimi</h3>
                <p>Eksploroni opsionet e fleksibël të financimit për ta bërë blerjen tuaj më të lehtë.</p>
            </div>
            <div class="service">
                <i class="fa fa-wrench"></i>
                <h3>Mirëmbajtja</h3>
                <p>Shërbime profesionale mirëmbajtjeje për të mbajtur automjetin tuaj në gjendje të shkëlqyer.</p>
            </div>
            <div class="service">
                <i class="fa fa-exchange-alt"></i>
                <h3>Ndërrimi i Automjeteve</h3>
                <p>Përmirësoni automjetin tuaj me procesin tonë të thjeshtë të ndërrimit.</p>
            </div>
        </div>
    </div>
</section>

<section id="testimonials" class="testimonials">
    <div class="container">
        <h2>Çfarë Thonë Klientët Tanë</h2>
        <div class="testimonial-list">
            <div class="testimonial">
                <p>"Përvoja më e mirë e blerjes së automjeteve që kam pasur ndonjëherë! Stafi profesional dhe një përzgjedhje e shkëlqyer."</p>
                <cite>Asdren Kodrolli</cite>
            </div>
            <div class="testimonial">
                <p>"Shërbimi dhe mbështetje fantastike. Fort e rekomanduar për këdo që kërkon një automjet të ri."</p>
                <cite>Qendrim Zejnullahu</cite>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <div class="container">
        <h2>Na Kontaktoni</h2>
        <form action="submit_form.php" method="post">
            <div class="form-group">
                <label for="name">Emri:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Emaili:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Mesazhi:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Dërgo Mesazhin</button>
        </form>
    </div>
</section>

<footer>
    <div class="footer-column">
        <h3>Na ndiqni</h3>
        <div class="social-media-icons">
            <a href="https://www.facebook.com"><i class="fab fa-facebook"></i></a>
            <a href="https://www.twitter.com"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com/"><i class="fab fa-instagram"></i></a>
        </div>
    <div class="container">
        <p>&copy; 2024 AutoSallon Malti - Vushtrri. Të drejtat e rezervuara.</p>
    </div>
</footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/js/all.min.js" integrity="sha512-P/5Q1fgRJy/nkWq6k2kCAV6U/d9d9C3cXgqCgXjzSkwUkOXtEoFQwD/Zv+4F6z5QL6Q5aFS7J2Pj8X9Wz4cdZQ==" crossorigin="anonymous" referrerpolicy="no-referrer" defer></script>
</body>
</html>
