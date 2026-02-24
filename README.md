
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portifolio</title>
    <style>
        body {
            font-family: Georgia, 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        nav {
            background-color: #ca1a1a;
            color: rgb(201, 154, 0);
            padding: 1rem;
        }
        nav h1 {
            color: #ff8801;
            margin: 0;
            font-size: 1.5rem;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: -moz-box;
            margin-right: 1rem;
        }
        nav ul li a {
            color: rgb(78, 233, 116);
            text-decoration:hsl(from color h s l);
        }
        skills {
            background-color: #34069e;
            color: rgb(68, 25, 102);
            padding: 2rem;
            text-align: border-box;
            skill-1{
                <h3>Web Development</h3>
                text-align: left;
                margin-bottom: 1rem;
            }
            skill-2{
                <h3>css</h3>
                text-align: right;
                margin-bottom: 1rem;
            }
            skill-3{
                <h3>JavaScript</h3>
                text-align: left;
                margin-bottom: 1rem;
            }
            skill-4{
                <h3>Frameworks</h3>
                text-align: right;
                margin-bottom: 1rem;
            }
        }
        section {
            padding: 2rem;
        }
        button {
            background-color: #f30a0a;
            color: rgb(255, 139, 139);
            border: none;
            border-radius: 4px;
            padding: 0.5rem 1rem;
            cursor: pointer;
        }
        footer {
            background-color: #06fa4f;
            color: rgb(0, 6, 56);
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>

<body>
    <!--NAVIGATION BAR-->
    <nav>
        <div>
            <h1>MR.BONI</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!--HERO/IMAGE* BIO SECTION-->
    <section id="about">
        <div>
            <img
                class="fit picture"
                src="https://avatars.githubusercontent.com/u/122380441?v=4"
                alt="Profile Photo of Boni"
                >
        </div>
        <!--Bio-->
        <div>
            <h2>Boni's Bio</h2>
            <p>Junior Web🌎 Developer</p>
            <p>Hi, I'm Boni! I'm a passionate web developer with a love for creating beautiful and functional websites.<br> With over 5 years of experience in the industry, I have a strong background in HTML, CSS, JavaScript, and various web development frameworks.<br> I enjoy working on both front-end and back-end projects, and I'm always eager to learn new technologies and improve my skills.
            </p>
        </div>
    </section>

    <!--SKILLS SECTION-->
    <section id="skills">
        <div>
            <h2>Skills</h2>
            <!--Skills Grid-->
            <div>
                <!--Skill 1-->
                <div>
                    <div>🌐</div>
                    <h3>Web Development</h3>
                    <p>Proficient in HTML, CSS, JavaScript, and various web development frameworks.</p>
                </div>
                <!--Skill 2-->
                <div>
                    <div>🎨</div>
                    <h3>css</h3>
                    <p>Skilled in creating responsive and visually appealing layouts using CSS.</p>
                </div>
                <!--Skill 3-->
                <div>
                    <div>⚡</div>
                    <h3>JavaScript</h3>
                    <p>Experienced in building interactive and dynamic web applications using JavaScript.</p>
                </div>
                <!--Skill 4-->
                <div>
                    <div>💻</div>
                    <h3>Frameworks</h3>
                    <p>Familiar with popular web development frameworks such as React, Angular, and Vue.js.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!--CONTACT SECTION-->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <!--Name field-->
            <div>
                <label>Name:</label>
                <input
                    type="text"
                    placeholder="Enter your name"
                >
            </div>
            <!--Email field-->
            <div>
                <label>Email:</label>
                <input
                    type="email"
                    placeholder="Enter your email"
                >
            </div>
            <!--Message field-->
            <div>
                <label>Message:</label>
                <textarea
                    rows="4"
                    placeholder="Enter your message"
                ></textarea>
            </div>
            <!--submit Button-->
            <button
                type="submit"
            >
                Send Message
            </button>
        </form>
    </section>  

    <!--FOOTER-->
    <footer>
        <p>&copy; 2026 Boni.Built with ❤️for 💻programing.</p>
    </footer>

</body>
</html>