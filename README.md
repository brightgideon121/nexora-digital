# nexora-digital
My first website project — NEXORA DIGITAL.

<!DOCTYPE html>
<html>
<head><link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexora Digital</title>
    <link rel="stylesheet" href="style.css">
</head>

<body><script src="script.js"></script>

    <h1>
<nav class="navbar">
    <div class="logo">NEXORA DIGITAL</div>

    <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</nav>
</h1>

    <h2><section id="home">
    <h1>Imagine More. Build Beyond.</h1>
    <p>Welcome to the Future of Technology.</p>
</section></p>

    <button onclick="showMessage()">
        Discover Our World
    </button>

    
<section id="contact" class="contact">
    <h2>Contact Nexora Digital</h2>

    <p>Have an idea? Let's build something amazing together.</p>

    <form id="contactForm">

        <input
            type="text"
            id="name"
            placeholder="Enter your name"
            required
        >

        <input
            type="email"
            id="email"
            placeholder="Enter your email"
            required
        >

        <textarea
            id="message"
            placeholder="Write your message here"
            required
        ></textarea>

        <button type="submit">Send Message</button>

    </form>
</section>

  section
        <p>
            We transform creative ideas into
            beautiful websites and intelligent
            digital experiences.
        </p>
    </section>

    <section class="services" id="services">

        <div class="service-card">
            <h2>Website Development</h2>
            <p>Creating modern websites.</p>
        </div>

        <div class="service-card">
            <h2>Artificial Intelligence</h2>
            <p>Exploring intelligent AI solutions.</p>
        </div>

        <div class="service-card">
            <h2>Digital Design</h2>
            <p>Creating beautiful digital designs.</p>
        </div>
    </section>

    <script src="script.js"></script>

</body>
</html>
