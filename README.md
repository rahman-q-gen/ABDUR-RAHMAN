ABDUR-RAHMAN/
│
├── index.html
├── work.html
├── work.css
├── work.js
│
└── images/
    └── work/
        ├── logo-01.jpg
        ├── banner-01.jpg
        ├── poster-01.jpg
        ├── social-01.jpg
        ├── website-01.jpg
        ├── data-01.jpg
        └── certificate-01.jpg


work.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Work | MD. ABDUR RAHMAN</title>

    <meta name="description"
          content="Portfolio and selected works of MD. ABDUR RAHMAN">

    <link rel="stylesheet" href="work.css">
</head>

<body>

<!-- ================= HEADER ================= -->

<header class="header">

    <div class="logo">
        MD. ABDUR <span>RAHMAN</span>
    </div>

    <nav class="navbar">

        <a href="index.html">HOME</a>

        <a href="index.html#about">ABOUT</a>

        <a href="work.html" class="active">WORK</a>

        <a href="index.html#services">SERVICES</a>

        <a href="index.html#contact">CONTACT</a>

    </nav>

    <a href="index.html#contact" class="hire-btn">
        HIRE ME ↗
    </a>

</header>


<!-- ================= WORK HERO ================= -->

<section class="work-hero">

    <p class="small-title">
        ✦ MY PORTFOLIO ✦
    </p>

    <h1>
        MY <span>WORK</span>
    </h1>

    <p class="hero-description">
        A collection of my creative, professional and technical projects.
    </p>

</section>


<!-- ================= FILTER ================= -->

<section class="portfolio-section">

    <div class="filter-buttons">

        <button class="filter-btn active"
                data-filter="all">
            ALL
        </button>

        <button class="filter-btn"
                data-filter="graphic">
            GRAPHIC DESIGN
        </button>

        <button class="filter-btn"
                data-filter="web">
            WEB
        </button>

        <button class="filter-btn"
                data-filter="it">
            IT
        </button>

        <button class="filter-btn"
                data-filter="data">
            DATA MANAGEMENT
        </button>

    </div>


    <!-- ================= PROJECT GRID ================= -->

    <div class="project-grid">


        <!-- PROJECT 01 -->

        <div class="project-card"
             data-category="graphic">

            <div class="project-image">

                <img src="images/work/logo-01.jpg"
                     alt="Logo Design">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/logo-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    GRAPHIC DESIGN
                </span>

                <h2>Logo Design</h2>

                <p>
                    Professional logo design created for branding
                    and business identity.
                </p>

                <div class="project-footer">

                    <span>
                        Adobe Illustrator
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 02 -->

        <div class="project-card"
             data-category="graphic">

            <div class="project-image">

                <img src="images/work/banner-01.jpg"
                     alt="Banner Design">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/banner-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    GRAPHIC DESIGN
                </span>

                <h2>Banner Design</h2>

                <p>
                    Modern promotional banner designed for
                    digital and print use.
                </p>

                <div class="project-footer">

                    <span>
                        Illustrator / Photoshop
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 03 -->

        <div class="project-card"
             data-category="graphic">

            <div class="project-image">

                <img src="images/work/poster-01.jpg"
                     alt="Poster Design">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/poster-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    GRAPHIC DESIGN
                </span>

                <h2>Poster Design</h2>

                <p>
                    Creative poster design with a modern
                    visual presentation.
                </p>

                <div class="project-footer">

                    <span>
                        Adobe Photoshop
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 04 -->

        <div class="project-card"
             data-category="graphic">

            <div class="project-image">

                <img src="images/work/social-01.jpg"
                     alt="Social Media Design">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/social-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    GRAPHIC DESIGN
                </span>

                <h2>Social Media Design</h2>

                <p>
                    Social media creative designed for
                    online marketing and promotion.
                </p>

                <div class="project-footer">

                    <span>
                        Photoshop / Illustrator
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 05 -->

        <div class="project-card"
             data-category="web">

            <div class="project-image">

                <img src="images/work/website-01.jpg"
                     alt="Portfolio Website">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/website-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    WEB
                </span>

                <h2>Portfolio Website</h2>

                <p>
                    Responsive personal portfolio website
                    developed using modern web technologies.
                </p>

                <div class="project-footer">

                    <span>
                        HTML / CSS / JavaScript
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 06 -->

        <div class="project-card"
             data-category="it">

            <div class="project-image">

                <img src="images/work/data-01.jpg"
                     alt="Data Management">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/data-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    IT
                </span>

                <h2>Data Management</h2>

                <p>
                    Organized and managed digital information
                    for efficient office workflow.
                </p>

                <div class="project-footer">

                    <span>
                        MS Excel / Data Management
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 07 -->

        <div class="project-card"
             data-category="data">

            <div class="project-image">

                <img src="images/work/data-01.jpg"
                     alt="Data Management Project">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/data-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    DATA MANAGEMENT
                </span>

                <h2>Data Management Project</h2>

                <p>
                    Data entry, organization and spreadsheet
                    management project.
                </p>

                <div class="project-footer">

                    <span>
                        Excel / Data Entry
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>



        <!-- PROJECT 08 -->

        <div class="project-card"
             data-category="graphic">

            <div class="project-image">

                <img src="images/work/certificate-01.jpg"
                     alt="Certificate Design">

                <div class="image-overlay">

                    <button class="view-image"
                            data-image="images/work/certificate-01.jpg">
                        VIEW IMAGE
                    </button>

                </div>

            </div>

            <div class="project-info">

                <span class="project-category">
                    GRAPHIC DESIGN
                </span>

                <h2>Certificate Design</h2>

                <p>
                    Professional certificate layout and
                    visual design.
                </p>

                <div class="project-footer">

                    <span>
                        Adobe Illustrator
                    </span>

                    <a href="#"
                       class="project-link">
                        VIEW PROJECT →
                    </a>

                </div>

            </div>

        </div>


    </div>

</section>


<!-- ================= IMAGE LIGHTBOX ================= -->

<div class="lightbox" id="lightbox">

    <button class="close-lightbox">
        ×
    </button>

    <img id="lightbox-image"
         src=""
         alt="Project Preview">

</div>


<!-- ================= FOOTER ================= -->

<footer class="footer">

    <p>
        © 2026 MD. ABDUR RAHMAN.
        All Rights Reserved.
    </p>

    <p>
        Creativity + Technology + Organization
    </p>

</footer>


<script src="work.js"></script>

</body>
</html>


work.css
/* =========================================
   GLOBAL
========================================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #070b12;
    color: #ffffff;
    min-height: 100vh;
}


/* =========================================
   HEADER
========================================= */

.header {
    height: 82px;
    width: 100%;
    padding: 0 5%;

    display: flex;
    align-items: center;
    justify-content: space-between;

    background: #070a10;

    border-bottom: 1px solid rgba(255,255,255,0.05);

    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 20px;
    font-weight: 800;
    letter-spacing: 1px;
    color: #08cfff;
}

.logo span {
    color: #b933ff;
}

.navbar {
    display: flex;
    gap: 32px;
}

.navbar a {
    color: #ffffff;
    text-decoration: none;

    font-size: 13px;
    font-weight: 700;

    transition: 0.3s;
}

.navbar a:hover,
.navbar a.active {
    color: #08d7ff;
}

.hire-btn {
    padding: 13px 22px;

    color: #fff;
    text-decoration: none;

    font-size: 12px;
    font-weight: 800;

    border-radius: 8px;

    background: linear-gradient(
        135deg,
        #ff16c7,
        #8d16ef
    );

    transition: 0.3s;
}

.hire-btn:hover {
    transform: translateY(-2px);
}


/* =========================================
   HERO
========================================= */

.work-hero {
    padding: 100px 20px 75px;

    text-align: center;

    background:
        radial-gradient(
            circle at 20% 40%,
            rgba(0, 220, 255, 0.14),
            transparent 35%
        ),
        radial-gradient(
            circle at 80% 40%,
            rgba(255, 0, 190, 0.14),
            transparent 35%
        );
}

.small-title {
    color: #00ddff;

    font-size: 14px;
    font-weight: 800;

    letter-spacing: 2px;

    margin-bottom: 25px;
}

.work-hero h1 {
    font-size: clamp(55px, 8vw, 100px);

    line-height: 1;

    font-weight: 900;

    margin-bottom: 25px;
}

.work-hero h1 span {
    background: linear-gradient(
        90deg,
        #00d9ff,
        #375eff,
        #bf2eff,
        #ff18a8
    );

    -webkit-background-clip: text;
    background-clip: text;

    color: transparent;
}

.hero-description {
    max-width: 650px;

    margin: auto;

    color: #aeb7c8;

    font-size: 16px;

    line-height: 1.7;
}


/* =========================================
   PORTFOLIO SECTION
========================================= */

.portfolio-section {
    width: 90%;
    max-width: 1250px;

    margin: auto;

    padding: 30px 0 100px;
}


/* =========================================
   FILTER
========================================= */

.filter-buttons {
    display: flex;

    justify-content: center;
    align-items: center;

    flex-wrap: wrap;

    gap: 12px;

    margin-bottom: 55px;
}

.filter-btn {
    padding: 12px 20px;

    border: 1px solid #263242;

    border-radius: 7px;

    background: #0c121c;

    color: #aeb8c8;

    font-size: 12px;
    font-weight: 800;

    cursor: pointer;

    transition: 0.3s;
}

.filter-btn:hover {
    border-color: #00d9ff;

    color: #ffffff;
}

.filter-btn.active {
    color: #ffffff;

    border-color: transparent;

    background: linear-gradient(
        90deg,
        #00bfe9,
        #435cff,
        #a82cff
    );
}


/* =========================================
   PROJECT GRID
========================================= */

.project-grid {

    display: grid;

    grid-template-columns:
        repeat(3, 1fr);

    gap: 28px;
}


/* =========================================
   PROJECT CARD
========================================= */

.project-card {

    background: #0c121b;

    border: 1px solid #1b2635;

    border-radius: 14px;

    overflow: hidden;

    transition:
        transform 0.35s,
        border-color 0.35s,
        box-shadow 0.35s;
}

.project-card:hover {

    transform: translateY(-8px);

    border-color: #00bfe9;

    box-shadow:
        0 15px 45px
        rgba(0, 200, 255, 0.12);
}


/* =========================================
   PROJECT IMAGE
========================================= */

.project-image {

    height: 240px;

    position: relative;

    overflow: hidden;

    background: #111827;
}

.project-image img {

    width: 100%;
    height: 100%;

    object-fit: cover;

    display: block;

    transition: transform 0.5s;
}

.project-card:hover
.project-image img {

    transform: scale(1.07);
}


/* =========================================
   IMAGE OVERLAY
========================================= */

.image-overlay {

    position: absolute;

    inset: 0;

    display: flex;

    justify-content: center;
    align-items: center;

    background: rgba(3, 8, 15, 0.72);

    opacity: 0;

    transition: 0.3s;
}

.project-card:hover
.image-overlay {

    opacity: 1;
}

.view-image {

    border: 1px solid #00d9ff;

    background: rgba(0, 210, 255, 0.1);

    color: #ffffff;

    padding: 12px 18px;

    border-radius: 6px;

    font-size: 11px;

    font-weight: 800;

    cursor: pointer;

    transition: 0.3s;
}

.view-image:hover {

    background: #00cfff;

    color: #071018;
}


/* =========================================
   PROJECT INFO
========================================= */

.project-info {

    padding: 24px;
}

.project-category {

    font-size: 10px;

    font-weight: 900;

    letter-spacing: 1.5px;

    color: #00d9ff;
}

.project-info h2 {

    font-size: 22px;

    margin: 10px 0;

    color: #ffffff;
}

.project-info p {

    color: #8995a8;

    font-size: 13px;

    line-height: 1.7;

    min-height: 65px;
}


/* =========================================
   PROJECT FOOTER
========================================= */

.project-footer {

    display: flex;

    align-items: center;

    justify-content: space-between;

    gap: 10px;

    margin-top: 20px;

    padding-top: 18px;

    border-top: 1px solid #1c2735;
}

.project-footer span {

    color: #7e8a9d;

    font-size: 10px;

    font-weight: 700;
}

.project-link {

    color: #ff25c8;

    text-decoration: none;

    font-size: 10px;

    font-weight: 900;

    white-space: nowrap;
}

.project-link:hover {

    color: #00d9ff;
}


/* =========================================
   LIGHTBOX
========================================= */

.lightbox {

    position: fixed;

    inset: 0;

    z-index: 9999;

    display: none;

    justify-content: center;
    align-items: center;

    padding: 40px;

    background: rgba(0,0,0,0.92);
}

.lightbox.show {

    display: flex;
}

.lightbox img {

    max-width: 90vw;

    max-height: 85vh;

    object-fit: contain;

    border-radius: 10px;

    box-shadow:
        0 20px 80px
        rgba(0,0,0,0.8);
}

.close-lightbox {

    position: absolute;

    top: 25px;
    right: 35px;

    border: none;

    background: transparent;

    color: #ffffff;

    font-size: 45px;

    cursor: pointer;

    line-height: 1;
}

.close-lightbox:hover {

    color: #ff20c4;
}


/* =========================================
   FOOTER
========================================= */

.footer {

    padding: 35px 20px;

    text-align: center;

    background: #05080d;

    border-top: 1px solid #151d28;

    color: #697588;

    font-size: 11px;

    line-height: 2;
}


/* =========================================
   RESPONSIVE
========================================= */

@media (max-width: 1000px) {

    .project-grid {

        grid-template-columns:
            repeat(2, 1fr);
    }

    .navbar {

        gap: 18px;
    }
}


@media (max-width: 700px) {

    .header {

        height: auto;

        padding: 20px;

        flex-direction: column;

        gap: 20px;
    }

    .navbar {

        flex-wrap: wrap;

        justify-content: center;

        gap: 15px;
    }

    .hire-btn {

        display: none;
    }

    .work-hero {

        padding-top: 70px;
    }

    .project-grid {

        grid-template-columns: 1fr;
    }

    .filter-buttons {

        gap: 8px;
    }

    .filter-btn {

        padding: 10px 14px;

        font-size: 10px;
    }

    .project-image {

        height: 230px;
    }

}



work.js
/* =========================================
   PORTFOLIO FILTER
========================================= */

const filterButtons =
    document.querySelectorAll(".filter-btn");

const projectCards =
    document.querySelectorAll(".project-card");


filterButtons.forEach(button => {

    button.addEventListener("click", () => {

        /* Remove active class */

        filterButtons.forEach(btn => {

            btn.classList.remove("active");

        });

        /* Add active class */

        button.classList.add("active");


        /* Selected category */

        const filter =
            button.getAttribute("data-filter");


        projectCards.forEach(card => {

            const category =
                card.getAttribute("data-category");


            if (
                filter === "all" ||
                category === filter
            ) {

                card.style.display = "block";

            } else {

                card.style.display = "none";

            }

        });

    });

});


/* =========================================
   IMAGE LIGHTBOX
========================================= */

const lightbox =
    document.getElementById("lightbox");

const lightboxImage =
    document.getElementById("lightbox-image");

const viewButtons =
    document.querySelectorAll(".view-image");

const closeButton =
    document.querySelector(".close-lightbox");


/* Open image */

viewButtons.forEach(button => {

    button.addEventListener("click", () => {

        const image =
            button.getAttribute("data-image");

        lightboxImage.src = image;

        lightbox.classList.add("show");

        document.body.style.overflow = "hidden";

    });

});


/* Close button */

closeButton.addEventListener("click", () => {

    closeLightbox();

});


/* Click outside image */

lightbox.addEventListener("click", event => {

    if (event.target === lightbox) {

        closeLightbox();

    }

});


/* ESC key */

document.addEventListener("keydown", event => {

    if (event.key === "Escape") {

        closeLightbox();

    }

});


function closeLightbox() {

    lightbox.classList.remove("show");

    document.body.style.overflow = "";

    lightboxImage.src = "";

}
