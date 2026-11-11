# nexora-digital
My first website project — NEXORA DIGITAL.

<!DOCTYPE html>
<html>
<head><link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexora Digital</title>
    <link rel="stylesheet" href="style.css">
</head> /* NEXORA DIGITAL - Professional Hero */

.hero {
    min-height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 60px 20px;
}

.brand-line {
    font-size: 14px;
    letter-spacing: 2px;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 56px;
    margin: 10px 0;
}

.hero h2 {
    font-size: 28px;
    margin: 10px 0 20px;
}

.hero p {
    max-width: 700px;
    line-height: 1.7;
}

.hero-button {
    display: inline-block;
    margin-top: 25px;
    padding: 14px 28px;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
}

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

    <section class="hero" id="home">

    <p class="brand-line">
        Innovation • Technology • Creativity • AI
    </p>

    <h1>NEXORA DIGITAL</h1>

    <h2>Imagine More. Build Beyond.</h2>

    <p>
        Welcome to the Future of Technology.
        We transform creative ideas into beautiful websites,
        intelligent AI solutions and powerful digital experiences.
    </p>

    <a href="#services" class="hero-button">
        Explore Our Services
    </a>
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
