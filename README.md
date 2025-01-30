<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="" viewport" content="" width=device-width, initial-scale="1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/f3ec613ece.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="christianjosh.png" alt="Josh">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Graphics / Creative Designer</p>
                <h1>Hi, I'm <span>Josh Christian</span><br>from Philippines</h1>
            </div>
        </div>
    </div>
    <!-----------about----------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="image_123650291 (1).JPG">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p> <br>My journey in web development began with a curiosity-driven exploration of HTML, CSS and
                        JavaScript which ignited my passion for coding. Since then, I have continuously honed my skills
                        and expanded my expertise staying abreast of the latest industry trends and technologies.</p>

                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web/App Interfaces</li>
                            <li><span>Web Development</span><br>Web/App Development</li>
                            <li><span>Computer Systems Servicing</span><br>Computer Systems and Network Maintenance</li>
                            <li><span>Proficiency in MS Office & Strong Skills in Using Editing Tools</span><br>MS. Excell, PowerPoint, Word, Adobe Photoshop, Figma & Canva</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2024 </span><br> Java Programming / TESDA TRAINING</li>
                            <li><span>2023 </span><br>Computer Systems Servicing / TESDA TRAINING</li>
                            <li><span>2022 - 2023</span><br>Customer Service Representative at Inspiro</li>
                            <li><span>2019 - 2021</span><br>Computer Attendant at HyperBlitz Gaming Corner</li>
                            <li><span>2019 </span><br>Internship at Hyudai as Accounting Staff</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2017 - 2019</span><br>Access Computer College Inc.<br>Information & Communication Technology<br>Computer Programming</li>
                            <li><span>2019 - 2022</span><br>Lady of Lourdes College Inc.<br>Bachelor of Secondary
                                Education Major in English</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!----------------Services-------------------->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>I specialize in providing comprehensive web design services tailored to meet the unique needs and
                        goals of my clients. My experienced designers and developers is dedicated to
                        delivering high-quality, visually stunning websites that effectively represent your brand and
                        drive results.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop"></i>
                    <h2>UI/UX Design</h2>
                    <p>I specialize in crafting exceptional user experiences through innovative UI/UX design solutions.
                        My mission is to create intuitive and visually captivating interfaces that engage users and
                        elevate your digital presence.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store"></i>
                    <h2>LOGO Design</h2>
                    <p>I specialize in creating visually compelling and memorable logos that resonate with your target
                        audience and effectively communicate your brand identity. My creativity, strategic thinking, and
                        attention to detail to craft logos that leave a
                        lasting impression.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!----------------portfolio---------------->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Works</h1>
            <div class="work-list">
                <div class="work">
                    <img src="Logo1.jpg">
                    <div class="layer">
                        <h3>Huge Bite Logo</h3>
                        <p>This Logo design named Huge Bite was created for my project in college.
                            It is used for an Entreupreneuship event week where I designed it for my business.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="logo4.jpg">
                    <div class="layer">
                        <h3>Impact Esport Logo</h3>
                        <p>I designed this logo for my team. This Logo design named Impact Esport was created for an
                            E-sport event. The Logo design was signify the gamers for this event.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="logo6.jpg">
                    <div class="layer">
                        <h3>PEI Sport Finishing Logo</h3>
                        <p>This PEI Sport Fishing is a Logo for a fishing sport event where it occured in Canada. It was
                            a simple task that it was given by my manager that live in Canada.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>
    <!------------------contact----------------->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-paper-plane"></i> contact: christianjoshua0414@gmail.com</p>
                    <p><i class="fa-solid fa-phone-volume"></i> +639950146553</p>
                    <div class="social-icons">
                        <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                        <a href=""><i class="fa-brands fa-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="Christian Joshua Pareño Resume.pdf" download class="btn btn2">Download Resume</a>
                </div>
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Email " required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright © Josh Christian. My Personal Portfolio <i class="fa-solid fa-heart"></i> </p>
        </div>
    </div>

    <script>

        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }

    </script>

    <script>
        var sidemeu = document.getElementById("sidemenu");

        function openmenu() {
            sidemeu.style.right = "0";
        }
        function closemenu() {
            sidemeu.style.right = "-200px";
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzPl-Y8DuN9yp-Y_GA9gFMtVTe6ym53bsy2SSR4kDgTkyY9fXvTDfWEyBshQCnw-1Ww/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")

        form.addEventListener('submit', e => {
            e.preventDefault()
            fetch(scriptURL, { method: 'POST', body: new FormData(form) })
                .then(response => {
                    msg.innerHTML = "Message sent successfully"
                    setTimeout(function () {
                        msg.innerHTML = ""
                    }, 5000)
                    form.reset()
                })
                .catch(error => console.error('Error!', error.message))
        })
    </script>
</body>

</html>
