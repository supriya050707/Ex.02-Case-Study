
# Ex02 Commercial Website
## Date:2/11/2026
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
HTML
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUMORA | Living Beautifully</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Announcement Bar -->
    <div class="announcement">
        FREE SHIPPING ON ORDERS ABOVE ₹2,999
    </div>

    <!-- Header -->
    <header class="header">
        <h1 class="logo">LUMORA<span>.</span></h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#collections">Collections</a>
            <a href="#featured">Featured</a>
            <a href="#about">Our Story</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#account" class="account-link">My Account ↗</a>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">

        <div class="hero-text">
            <p class="eyebrow">DESIGNED FOR BETTER LIVING</p>

            <h2>Make Room<br>For Beautiful<br><em>Things.</em></h2>

            <p class="hero-description">
                Thoughtfully selected furniture, home decor
                and lifestyle essentials that make every
                corner feel special.
            </p>

            <a href="#collections" class="primary-btn">
                Explore Collection →
            </a>

            <div class="hero-note">
                <span>01 — 04</span>
                <span>CURATED FOR YOUR SPACE</span>
            </div>
        </div>

        <div class="hero-photo">
            <img
                src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?w=1000"
                alt="Elegant modern living room">
            <div class="photo-label">
                <span>THE ART OF LIVING</span>
                <strong>Simple. Natural. Timeless.</strong>
            </div>
        </div>

    </section>

    <!-- Category Section -->
    <section class="collections" id="collections">

        <div class="section-heading">
            <div>
                <p class="eyebrow">EXPLORE OUR WORLD</p>
                <h2>Shop by Category</h2>
            </div>
            <p>Beautiful essentials for every part of your home.</p>
        </div>

        <div class="category-grid">

            <div class="category furniture">
                <img
                    src="https://images.unsplash.com/photo-1555041469-a586c61ea9bc?w=700"
                    alt="Modern living room furniture">
                <div class="category-info">
                    <span>01 / COMFORT</span>
                    <h3>Furniture</h3>
                    <a href="#featured">Discover →</a>
                </div>
            </div>

            <div class="category decor">
                <img
                    src="https://images.unsplash.com/photo-1490312278390-ab64016e0aa9?w=700"
                    alt="Decorative home accessories">
                <div class="category-info">
                    <span>02 / DETAILS</span>
                    <h3>Home Decor</h3>
                    <a href="#featured">Discover →</a>
                </div>
            </div>

            <div class="category lighting">
                <img
                    src="https://images.unsplash.com/photo-1507473885765-e6ed057f782c?w=700"
                    alt="Decorative lighting">
                <div class="category-info">
                    <span>03 / AMBIENCE</span>
                    <h3>Lighting</h3>
                    <a href="#featured">Discover →</a>
                </div>
            </div>

        </div>
    </section>

    <!-- Featured Products -->
    <section class="featured" id="featured">

        <div class="featured-heading">
            <p class="eyebrow">THE LUMORA EDIT</p>
            <h2>Objects With Character.</h2>
            <p>Our favourite pieces, selected just for you.</p>
        </div>

        <div class="product-grid">

            <div class="product">
                <div class="product-image">
                    <img
                        src="https://images.unsplash.com/photo-1499933374294-4584851497cc?w=600"
                        alt="Minimal wooden work desk">
                    <span class="product-tag">BESTSELLER</span>
                </div>
                <h3>Nordic Work Desk</h3>
                <p>Solid Wood Collection</p>
                <strong>₹8,499</strong>
            </div>

            <div class="product">
                <div class="product-image">
                    <img
                        src="https://images.unsplash.com/photo-1578500494198-246f612d3b3d?w=600"
                        alt="Modern ceramic vase">
                    <span class="product-tag">NEW ARRIVAL</span>
                </div>
                <h3>Clay Ceramic Vase</h3>
                <p>Handcrafted Decor</p>
                <strong>₹1,299</strong>
            </div>

            <div class="product">
                <div class="product-image">
                    <img
                        src="https://images.unsplash.com/photo-1507473885765-e6ed057f782c?w=600"
                        alt="Contemporary table lamp">
                </div>
                <h3>Ambient Table Lamp</h3>
                <p>Modern Lighting</p>
                <strong>₹2,199</strong>
            </div>

            <div class="product">
                <div class="product-image">
                    <img
                        src="https://images.unsplash.com/photo-1600210491369-e753d80a41f3?w=600"
                        alt="Elegant interior decor">
                </div>
                <h3>Living Space Set</h3>
                <p>Premium Lifestyle</p>
                <strong>₹5,999</strong>
            </div>

        </div>
    </section>

    <!-- Brand Story -->
    <section class="story" id="about">

        <div class="story-image">
            <img
                src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?w=900"
                alt="Beautifully designed home interior">
        </div>

        <div class="story-content">
            <p class="eyebrow">A LITTLE ABOUT US</p>
            <h2>Less Ordinary.<br><em>More Meaningful.</em></h2>

            <p>
                At LUMORA, we believe that a beautiful home
                is created through thoughtful choices.
                We bring together timeless designs, natural
                textures and everyday functionality.
            </p>

            <a href="#contact" class="secondary-btn">
                Discover Our Story →
            </a>
        </div>

    </section>

    <!-- Promotional Section -->
    <section class="offer">
        <p class="eyebrow">A SPECIAL SOMETHING FOR YOU</p>
        <h2>Good Spaces. Better Days.</h2>
        <p>Get 15% OFF on your first purchase.</p>
        <a href="#featured">SHOP THE COLLECTION →</a>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">

        <div>
            <p class="eyebrow">WE WOULD LOVE TO HEAR FROM YOU</p>
            <h2>Let's Connect.</h2>
        </div>

        <div class="contact-details">
            <p>Email: hello@lumora.com</p>
            <p>Phone: +91 9876543210</p>
            <p>Location: Chennai, India</p>
        </div>

    </section>

    <!-- Account -->
    <section class="account" id="account">
        <h2>Become Part of LUMORA.</h2>
        <p>Join our community for new collections and special offers.</p>
        <a href="#contact">GET IN TOUCH →</a>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-top">
            <h2>LUMORA<span>.</span></h2>
            <p>Creating spaces that feel like home.</p>
        </div>

        <div class="footer-bottom">
            <p>Instagram · Facebook · Pinterest</p>
            <p>© 2026 LUMORA. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>

```
CSS
```

/* GENERAL STYLING */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'Georgia', serif;
    background: #f4efe6;
    color: #33372c;
}

/* ANNOUNCEMENT */
.announcement {
    background: #a34f36;
    color: white;
    text-align: center;
    padding: 10px;
    font-family: Arial, sans-serif;
    font-size: 11px;
    letter-spacing: 2px;
}

/* HEADER */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 25px 7%;
    background: #f4efe6;
    gap: 25px;
}

.logo {
    font-size: 32px;
    letter-spacing: 3px;
    color: #343b2d;
}

.logo span,
footer h2 span {
    color: #a34f36;
}

nav {
    display: flex;
    gap: 27px;
    flex-wrap: wrap;
}

nav a {
    text-decoration: none;
    color: #45483d;
    font-family: Arial, sans-serif;
    font-size: 13px;
    transition: 0.3s;
}

nav a:hover {
    color: #a34f36;
}

.account-link {
    text-decoration: none;
    color: #a34f36;
    font-family: Arial, sans-serif;
    font-size: 13px;
    border-bottom: 1px solid #a34f36;
    padding-bottom: 5px;
}

/* HERO SECTION */
.hero {
    display: flex;
    align-items: center;
    background: #e9dfcf;
    padding: 55px 7%;
    gap: 55px;
    min-height: 570px;
}

.hero-text {
    flex: 0.85;
}

.eyebrow {
    color: #a34f36;
    font-family: Arial, sans-serif;
    font-size: 11px;
    font-weight: bold;
    letter-spacing: 3px;
    margin-bottom: 22px;
}

.hero h2 {
    font-size: 65px;
    line-height: 1.12;
    font-weight: normal;
    color: #343b2d;
}

.hero h2 em,
.story h2 em {
    color: #a34f36;
    font-weight: normal;
}

.hero-description {
    font-family: Arial, sans-serif;
    color: #6d6a5e;
    line-height: 1.9;
    margin: 22px 0 30px;
    max-width: 400px;
    font-size: 14px;
}

.primary-btn {
    display: inline-block;
    background: #a34f36;
    color: white;
    padding: 16px 25px;
    text-decoration: none;
    font-family: Arial, sans-serif;
    font-size: 12px;
    letter-spacing: 1px;
    transition: 0.3s;
}

.primary-btn:hover {
    background: #343b2d;
    transform: translateY(-3px);
}

.hero-note {
    display: flex;
    gap: 35px;
    margin-top: 65px;
    color: #797366;
    font-family: Arial, sans-serif;
    font-size: 10px;
    letter-spacing: 1px;
}

.hero-photo {
    flex: 1.15;
    position: relative;
}

.hero-photo img {
    width: 100%;
    height: 440px;
    object-fit: cover;
    display: block;
}

.photo-label {
    position: absolute;
    bottom: 20px;
    left: 20px;
    background: #f4efe6;
    padding: 17px 22px;
    display: flex;
    flex-direction: column;
    gap: 7px;
}

.photo-label span {
    font-family: Arial, sans-serif;
    font-size: 9px;
    letter-spacing: 2px;
    color: #a34f36;
}

.photo-label strong {
    font-size: 15px;
    font-weight: normal;
}

/* COLLECTIONS */
.collections {
    padding: 85px 7%;
}

.section-heading {
    display: flex;
    justify-content: space-between;
    align-items: end;
    margin-bottom: 35px;
    gap: 20px;
}

.section-heading h2,
.featured-heading h2 {
    font-size: 39px;
    font-weight: normal;
}

.section-heading > p {
    font-family: Arial, sans-serif;
    font-size: 13px;
    color: #777365;
}

.category-grid {
    display: flex;
    gap: 22px;
    align-items: stretch;
}

.category {
    flex: 1;
    position: relative;
    height: 390px;
    overflow: hidden;
    background: #ddd;
}

.category img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: 0.6s;
}

.category:hover img {
    transform: scale(1.07);
}

.category-info {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 25px;
    color: white;
    background: linear-gradient(transparent, #000000b5);
}

.category-info span {
    font-family: Arial, sans-serif;
    font-size: 10px;
    letter-spacing: 2px;
}

.category-info h3 {
    font-size: 28px;
    font-weight: normal;
    margin: 8px 0;
}

.category-info a {
    color: white;
    font-family: Arial, sans-serif;
    font-size: 12px;
    text-decoration: none;
    border-bottom: 1px solid white;
    padding-bottom: 5px;
}

/* FEATURED PRODUCTS */
.featured {
    background: #e8e3d8;
    padding: 80px 7%;
}

.featured-heading {
    text-align: center;
    margin-bottom: 45px;
}

.featured-heading > p:last-child {
    font-family: Arial, sans-serif;
    color: #777365;
    font-size: 13px;
    margin-top: 12px;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: center;
}

.product {
    flex: 1 1 220px;
    max-width: 280px;
}

.product-image {
    height: 290px;
    position: relative;
    overflow: hidden;
    background: #d9d1c4;
}

.product-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: 0.5s;
}

.product:hover img {
    transform: scale(1.06);
}

.product-tag {
    position: absolute;
    top: 15px;
    left: 15px;
    background: #f4efe6;
    color: #a34f36;
    padding: 8px 10px;
    font-family: Arial, sans-serif;
    font-size: 9px;
    letter-spacing: 1px;
}

.product h3 {
    font-size: 19px;
    font-weight: normal;
    margin-top: 17px;
}

.product p {
    font-family: Arial, sans-serif;
    color: #817c70;
    font-size: 12px;
    margin: 8px 0;
}

.product strong {
    color: #a34f36;
    font-family: Arial, sans-serif;
    font-size: 15px;
}

/* OUR STORY */
.story {
    display: flex;
    align-items: center;
    gap: 75px;
    padding: 90px 10%;
    background: #f4efe6;
}

.story-image {
    flex: 1;
}

.story-image img {
    width: 100%;
    height: 420px;
    object-fit: cover;
}

.story-content {
    flex: 1;
}

.story h2 {
    font-size: 43px;
    line-height: 1.3;
    font-weight: normal;
    margin-bottom: 25px;
}

.story-content > p:not(.eyebrow) {
    font-family: Arial, sans-serif;
    color: #777365;
    line-height: 2;
    font-size: 13px;
    margin-bottom: 28px;
}

.secondary-btn {
    color: #a34f36;
    text-decoration: none;
    font-family: Arial, sans-serif;
    font-size: 12px;
    border-bottom: 1px solid #a34f36;
    padding-bottom: 8px;
}

/* OFFER */
.offer {
    text-align: center;
    padding: 75px 20px;
    background: #59634a;
    color: white;
}

.offer .eyebrow {
    color: #e6c9a5;
}

.offer h2 {
    font-size: 42px;
    font-weight: normal;
    margin-bottom: 15px;
}

.offer p:not(.eyebrow) {
    font-family: Arial, sans-serif;
    font-size: 14px;
    margin-bottom: 30px;
}

.offer a {
    display: inline-block;
    color: #343b2d;
    background: #e9dfcf;
    text-decoration: none;
    padding: 15px 25px;
    font-family: Arial, sans-serif;
    font-size: 11px;
    letter-spacing: 1px;
    transition: 0.3s;
}

.offer a:hover {
    background: white;
}

/* CONTACT */
.contact {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
    padding: 70px 10%;
}

.contact h2 {
    font-size: 40px;
    font-weight: normal;
}

.contact-details p {
    font-family: Arial, sans-serif;
    color: #777365;
    font-size: 13px;
    margin: 12px 0;
}

/* ACCOUNT */
.account {
    text-align: center;
    padding: 55px 20px;
    background: #e9dfcf;
}

.account h2 {
    font-size: 31px;
    font-weight: normal;
}

.account p {
    font-family: Arial, sans-serif;
    font-size: 13px;
    color: #777365;
    margin: 15px 0 22px;
}

.account a {
    color: #a34f36;
    font-family: Arial, sans-serif;
    font-size: 12px;
    text-decoration: none;
    border-bottom: 1px solid #a34f36;
    padding-bottom: 6px;
}

/* FOOTER */
footer {
    background: #343b2d;
    color: #f4efe6;
    padding: 40px 7% 20px;
}

.footer-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 35px;
}

.footer-top h2 {
    font-size: 30px;
    letter-spacing: 3px;
}

.footer-top p,
.footer-bottom {
    font-family: Arial, sans-serif;
    font-size: 11px;
    color: #d2cbbc;
}

.footer-bottom {
    border-top: 1px solid #ffffff35;
    padding-top: 20px;
    display: flex;
    justify-content: space-between;
    gap: 15px;
}

/* RESPONSIVE DESIGN */
@media (max-width: 850px) {

    .header {
        flex-direction: column;
    }

    nav {
        justify-content: center;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero h2 {
        font-size: 48px;
    }

    .hero-description {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-note {
        justify-content: center;
        margin: 30px 0;
    }

    .hero-photo {
        width: 100%;
    }

    .category-grid {
        flex-wrap: wrap;
    }

    .category {
        min-width: 45%;
    }

    .story {
        flex-direction: column;
    }

    .contact {
        flex-direction: column;
        text-align: center;
    }
}

@media (max-width: 550px) {

    .hero h2 {
        font-size: 38px;
    }

    .section-heading {
        flex-direction: column;
        align-items: flex-start;
    }

    .category {
        min-width: 100%;
    }

    .story h2 {
        font-size: 34px;
    }

    .offer h2 {
        font-size: 30px;
    }

    .footer-top,
    .footer-bottom {
        flex-direction: column;
        text-align: center;
        gap: 15px;
    }

    .product {
        max-width: 100%;
    }
}

```
## OUTPUT

<img width="1910" height="890" alt="Screenshot 2026-11-02 143948" src="https://github.com/user-attachments/assets/4981c1f9-162f-48d6-b90a-5d173feb1030" />

<img width="1902" height="831" alt="Screenshot 2026-11-02 143955" src="https://github.com/user-attachments/assets/6c06b0ca-be06-4a21-a4b2-a94af3103be5" />

<img width="1917" height="860" alt="Screenshot 2026-11-02 144006" src="https://github.com/user-attachments/assets/11f65386-754b-435e-9826-a617233b296e" />

<img width="1892" height="741" alt="image" src="https://github.com/user-attachments/assets/e2402fe2-578a-42ba-a03b-483196a0c5ae" />

<img width="1886" height="652" alt="Screenshot 2026-11-02 144033" src="https://github.com/user-attachments/assets/3784314e-cbae-435c-a5cd-ecfa1e57a991" />

<img width="1890" height="460" alt="Screenshot 2026-11-02 144044" src="https://github.com/user-attachments/assets/d17d1f1f-d76c-4568-8dd8-1153047b853f" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
