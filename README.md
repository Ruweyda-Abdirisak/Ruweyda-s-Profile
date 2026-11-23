<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rowdo Abdi | IT Specialist & Web Developer</title>
    <!-- Boxicons for Icons -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--===== HEADER =====-->
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#" class="nav__logo">Rowdo Abdi</a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                    <li class="nav__item"><a href="#work" class="nav__link">Projects</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>

            <div class="nav__toggle" id="nav-toggle">
                <i class='bx bx-menu'></i>
            </div>
        </nav>
    </header>

    <main class="l-main">
        <!--===== HOME =====-->
        <section class="home bd-grid" id="home">
            <div class="home__data">
                <h1 class="home__title">
                    Hi, I'm <span class="home__title-color">Rowdo Abdi</span><br>
                    IT Specialist &amp;<br>Web Developer
                </h1>
                <p class="home__description">
                    Computer Science student passionate about building responsive web applications, database systems, and secure network infrastructures.
                </p>
                <a href="#contact" class="button">Hire / Contact Me</a>
            </div>
        </section>

        <!--===== ABOUT =====-->
        <section class="about section" id="about">
            <h2 class="section-title">About Me</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="img.jpg" alt="Rowdo Abdi">
                </div>

                <div>
                    <h2 class="about__subtitle">IT Background &amp; Web Development</h2>
                    <p class="about__text">
                        I am a dedicated Computer Science &amp; Information Technology student with practical experience in full-stack web development, relational database administration, and network management. 
                    </p>
                    <p class="about__text">
                        From designing dynamic web systems using <strong>HTML, CSS, JavaScript, PHP, and Python (Flask)</strong> to configuring enterprise networks and managing MySQL &amp; Oracle databases, I focus on creating reliable, user-centered technology solutions.
                    </p>
                </div>
            </div>
        </section>

        <!--===== SKILLS =====-->
        <section class="skills section" id="skills">
            <h2 class="section-title">Technical Skills</h2>

            <div class="skills__container bd-grid">
                <div>
                    <h2 class="skills__subtitle">Professional Expertise</h2>
                    <p class="skills__text">
                        Combining a solid foundation in Information Technology with modern web development practices to build scalable applications.
                    </p>

                    <!-- Skill 1 -->
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bx-code-alt skills__icon'></i>
                            <span class="skills__name">Frontend (HTML5, CSS3, JavaScript)</span>
                        </div>
                        <div class="skills__bar skills__html"></div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>

                    <!-- Skill 2 -->
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bx-server skills__icon'></i>
                            <span class="skills__name">Backend (PHP, Python Flask, Java JSP)</span>
                        </div>
                        <div class="skills__bar skills__css"></div>
                        <div>
                            <span class="skills__percentage">80%</span>
                        </div>
                    </div>

                    <!-- Skill 3 -->
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bx-data skills__icon'></i>
                            <span class="skills__name">Databases (MySQL, MariaDB, Oracle)</span>
                        </div>
                        <div class="skills__bar skills__js"></div>
                        <div>
                            <span class="skills__percentage">80%</span>
                        </div>
                    </div>

                    <!-- Skill 4 -->
                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bx-network-chart skills__icon'></i>
                            <span class="skills__name">IT Infrastructure &amp; Networking</span>
                        </div>
                        <div class="skills__bar skills__ux"></div>
                        <div>
                            <span class="skills__percentage">85%</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--===== WORK / PROJECTS =====-->
        <section class="work section" id="work">
            <h2 class="section-title">Featured Projects</h2>

            <div class="work__container bd-grid">
                <a href="#work" class="work__img" title="Complaint Management System (PHP & MySQL)">
                    <img src="work1.jpg" alt="Complaint Management System">
                </a>
                <a href="#work" class="work__img" title="E-Commerce Grocery Store (Python Flask)">
                    <img src="work2.jpg" alt="Grocery Store Web Application">
                </a>
                <a href="#work" class="work__img" title="Inventory Management System (PHP & MySQL)">
                    <img src="work3.jpg" alt="Inventory Management System">
                </a>
                <a href="#work" class="work__img" title="Cafe Management System (Java JSP & MySQL)">
                    <img src="work4.jpg" alt="Cafe Management System">
                </a>
                <a href="#work" class="work__img" title="HR Management System (Python & MySQL)">
                    <img src="work5.jpg" alt="HR Management System">
                </a>
                <a href="#work" class="work__img" title="IoT Smart Street Light System">
                    <img src="work6.jpg" alt="IoT Smart Street Light Controller">
                </a>
            </div>
        </section>

        <!--===== CONTACT =====-->
        <section class="contact section" id="contact">
            <h2 class="section-title">Get In Touch</h2>

            <div class="contact__container bd-grid">
                <form action="" class="contact__form">
                    <input type="text" placeholder="Your Name" class="contact__input" required>
                    <input type="email" placeholder="Your Email" class="contact__input" required>
                    <textarea name="message" id="message" cols="0" rows="8" placeholder="Write your message here..." class="contact__input" required></textarea>
                    <input type="submit" value="Send Message" class="contact__button button">
                </form>
            </div>
        </section>
    </main>

    <!--===== FOOTER =====-->
    <footer class="footer">
        <p class="footer__title">Rowdo Abdi</p>
        <div class="footer__social">
            <a href="https://github.com/" target="_blank" class="footer__icon" aria-label="GitHub"><i class='bx bxl-github'></i></a>
            <a href="https://linkedin.com/" target="_blank" class="footer__icon" aria-label="LinkedIn"><i class='bx bxl-linkedin'></i></a>
            <a href="#" class="footer__icon" aria-label="Twitter"><i class='bx bxl-twitter'></i></a>
        </div>
        <p class="footer__copy">&#169; 2026 Rowdo Abdi. All rights reserved.</p>
    </footer>
</body>
</html>
