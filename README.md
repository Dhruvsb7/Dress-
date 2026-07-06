<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DRIFT — Objects for the Drift</title>
    <link rel="stylesheet" href="style.css">
    <!-- Importing a clean sans-serif font for the minimalist look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Header Navigation -->
    <header class="navbar">
        <a href="#" class="brand-logo">DRIFT</a>
        <button class="menu-toggle" id="menuToggle" aria-label="Toggle Menu">
            <span class="menu-text">MENU</span>
            <span class="hamburger-icon">
                <span></span>
                <span></span>
            </span>
        </button>
    </header>

    <!-- Fullscreen Overlay Menu -->
    <nav class="fullscreen-menu" id="fullscreenMenu">
        <div class="menu-links">
            <a href="#" class="menu-item">SHOP</a>
            <a href="#" class="menu-item">COLLECTIONS</a>
            <a href="#" class="menu-item">ABOUT</a>
            <a href="#" class="menu-item">CONTACT</a>
        </div>
    </nav>

    <main>
        <!-- Hero Section -->
        <section class="hero">
            <!-- Background Image Container -->
            <div class="hero-bg">
                <img src="https://images.unsplash.com/photo-1617137968427-85924c800a22?q=80&w=1200&auto=format&fit=crop" alt="Model wearing a long tailored winter coat standing against an architectural concrete background">
            </div>
            
            <div class="hero-content">
                <h1 class="hero-title">OBJECTS<br>FOR THE<br>DRIFT.</h1>
                <p class="hero-subtitle">
                    Precise garments designed for the modern transit. 
                    Structured for longevity, cut for the body in motion.
                </p>
                <a href="#" class="btn-primary">SHOP COLLECTION</a>
            </div>
        </section>

        <!-- The Edit Section -->
        <section class="curation-section">
            <div class="section-header">
                <span class="section-number">01 /</span>
                <span class="section-tag">CURATION</span>
                <h2 class="section-title">THE EDIT</h2>
            </div>

            <!-- Asymmetric Product Grid Layout -->
            <div class="product-grid">
                <div class="product-card tall-card">
                    <div class="img-wrapper">
                        <img src="https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?q=80&w=800&auto=format&fit=crop" alt="Brown textured heavy knit fabric detail">
                    </div>
                    <div class="product-info">
                        <span class="product-num">01.</span>
                        <span class="product-name">HEAVY KNIT</span>
                    </div>
                </div>

                <div class="product-card shifted-card">
                    <div class="img-wrapper">
                        <img src="https://images.unsplash.com/photo-1608256246200-53e635b5b65f?q=80&w=800&auto=format&fit=crop" alt="Minimalist premium black leather boots">
                    </div>
                    <div class="product-info">
                        <span class="product-num">02.</span>
                        <span class="product-name">RAW HIDE</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Architecture of Dress Block (Dark Theme Accent) -->
        <section class="manifesto-section">
            <div class="container-narrow">
                <span class="manifesto-tag">ARCHITECTURE OF DRESS</span>
                <p class="manifesto-text">
                    We believe in the <span class="highlight-text">reduction of noise</span>. Each piece is a response to the chaos of modern life—a uniform that simplifies the morning and elevates the evening.
                </p>
                <div class="accent-line"></div>
            </div>
        </section>

        <!-- Testimonial Quote Block -->
        <section class="testimonial-section">
            <div class="container-narrow">
                <span class="quote-mark">“</span>
                <blockquote class="testimonial-quote">
                    "The fit is clinical. It's the first time a jacket felt like it was built specifically for my frame."
                </blockquote>
                <cite class="testimonial-author">MARCUS V. — ARCHITECT</cite>
            </div>
        </section>

        <!-- Newsletter Join Section -->
        <section class="newsletter-section">
            <div class="newsletter-box">
                <h3 class="newsletter-title">JOIN THE DRIFT</h3>
                <p class="newsletter-subtitle">Subscribers receive first access to seasonal drops and archival releases.</p>
                
                <form class="newsletter-form" onsubmit="event.preventDefault();">
                    <div class="input-group">
                        <input type="email" placeholder="EMAIL ADDRESS" required aria-label="Email address submission">
                    </div>
                    <button type="submit" class="btn-submit">SUBSCRIBE</button>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer Area -->
    <footer class="footer">
        <div class="footer-top">
            <span class="footer-logo">DRIFT</span>
            <div class="footer-socials">
                <a href="#">IG</a>
                <a href="#">TW</a>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 DRIFT ARCHIVE. ALL RIGHTS RESERVED.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
