# index_html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />
    <title>Document</title>
  </head>
  <body>
    <section class="menu">
      <button id="close-menu">&times;</button>
      <nav>
        <ul>
          <li>
            <a href="#about-me">About Me</a>
          </li>
          <li>
            <a href="#qualifications">Qualifications</a>
          </li>
          <li>
            <a href="#hobbies">Hobbies</a>
          </li>
          <li>
            <a href="#technologies">Technologies</a>
          </li>
          <li>
            <a href="#contact-me">Contact</a>
          </li>
        </ul>
      </nav>
    </section>
    <header class="header">
      <nav class="default-nav">
        <section>
        <a href="#about-me">About Me</a>
        <a href="#qualifications">Qualifications</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#technologies">Technologies</a>
        <a href="#contact-me">Contact</a>
        </section>
      </nav>
      <nav class="mobile-nav">
        <button id="menu-button">Menu</button>
      </nav>
    </header>
    <main class="container">
      <article class="intro">
        <img id="profile-image" src="profile2.png" alt="my profile pic" />
        <h1>Hi!! I'm Shibani</h1>
        <p>I am a <span id="dynamic-text" class="dynamic-text-color"></span></p>
        <p class="social">
          <a href="https://github.com/ShibaniBasa" target="_blank">
            <img
              src="https://t4.ftcdn.net/jpg/02/50/30/59/240_F_250305943_sDC6la1N1fDl3bLgfLxOkQwItIodsdMb.jpg"
              alt=""
            />
          </a>
          <a href="instagram.com/_shivanibasa_" target="_blank">
            <img
              src="https://www.iconpacks.net/icons/3/free-icon-instagram-logo-8869.png"
              alt=""
            />
          </a>
          <a href="www.linkedin.com/in/shibanibasa" target="_blank">
            <img
              src="https://www.iconpacks.net/icons/1/free-icon-linkedin-130.png"
              alt=""
            />
          </a>
        </p>
      </article>
      <section id="about-me">
        <h2>About me</h2>

        <p>
          A passionate learner and intriguing to acquire skills in various
          skills. Eager to contribute to team's success through hard work and
          excellent organizational skills.
          <br />
          Have written various articles and quotes which were printed in
          school magazines.I am interested in learning various tech domains
          and I'm keen to know a lot about web designs and machine learning.
          Presently I am aspiring to become a web designer.
          <br />
          Overall I'm a tech Dedicated and enthusiastic student eager to seek
          knowledge and utilize broad educational background with excellent
          analytical, technical and programming skills to thrive as an
          entry-level intern.
          <br />
        </p>
      </section>

      <section id="qualifications">
        <h2>Qualifications</h2>
        <ol>
          <li>Pursuing Btech from KIIT(2021-25)</li>
          <li>12th from SSSVV,Baripada(2021)</li>
          <li>10th from SSSVV,Baripada(2019)</li>
        </ol>
      </section>
      <hr />

      <section id="hobbies">
        <h2>Hobbies</h2>
        <ul>
          <li>Badminton</li>
          <li>Travelling</li>
          <li>Coding</li>
        </ul>
      </section>
      <hr />
      <section id="technologies">
        <h2>Technologies</h2>
        <section class="container">
          <section class="card">
            <header>
              <h1>Frontend</h1>
            </header>
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
            </ul>
          </section>
          <section class="card">
            <header>
              <h1>Designing</h1>
            </header>
            <ul>
              <li>Figma</li>
              <li>Adobe</li>
            </ul>
          </section>
          <section class="card">
            <header>
              <h1>Database</h1>
            </header>
            <ul>
              <li>MySQL</li>
            </ul>
          </section>
        </section>
      </section>
    </section>
    <section id="contact-me">
      <form name="contact" id="contact" method="POST" data-netlify="true">
        <h1>Contact Me</h1>
        <section>
          <label for="firstName">First Name</label>
          <input type="text" name="firstName" id="firstName" required />
        </section>
        <section>
          <label for="lastName">Last Name</label>
          <input type="text" name="lastName" id="lastName" required />
        </section>
        <section>
          <label for="messager">Message</label>
          <textarea name="message" id="message" cols="30" rows="10" wrap="physical"></textarea>
        </section>
        <button type="submit">Send</button>
      </form>
      </section>
    </main>
    <footer>
      Made with ❤️ by Shibani...
    </footer>
    <script src="main.js"></script>
    <script src="menu.js"></script>
  </body>
</html>
