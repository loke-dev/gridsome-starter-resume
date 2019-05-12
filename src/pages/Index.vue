<template>
  <Layout>
    <div class="container-fluid p-0">
      <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
        <div class="w-100">
          <h1 class="mb-0">
            Loke
            <span class="text-primary">Carlsson</span>
          </h1>
          <div class="subheading mb-5">
            9695 Foo street · Bar town, CO 93440 · (123) 456-7890 ·
            <a
              href="mailto:name@email.com"
            >name@email.com</a>
          </div>
          <p
            class="lead mb-5"
          >I am experienced in leveraging agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition.</p>
          <div class="social-icons">
            <a
              href="https://linkedin.com/in/lokecarlsson"
              target="_blank"
              rel="noopener noreferrer"
            >
              <font-awesome :icon="['fab', 'linkedin']"/>
            </a>
            <a href="https://github.com/LokeCarlsson" target="_blank" rel="noopener noreferrer">
              <font-awesome :icon="['fab', 'github']"/>
            </a>
            <a href="https://twitter.com/carlssonloke" target="_blank" rel="noopener noreferrer">
              <font-awesome :icon="['fab', 'twitter']"/>
            </a>
            <a
              href="https://www.facebook.com/carlssonloke"
              target="_blank"
              rel="noopener noreferrer"
            >
              <font-awesome :icon="['fab', 'facebook']"/>
            </a>
          </div>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex justify-content-center" id="experience">
        <div class="w-100">
          <h2 class="mb-5">Experience</h2>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
            <div class="resume-content">
              <h3 class="mb-0">Senior Web Developer</h3>
              <div class="subheading mb-3">Intelitec Solutions</div>
              <p>Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">March 2013 - Present</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
            <div class="resume-content">
              <h3 class="mb-0">Web Developer</h3>
              <div class="subheading mb-3">Intelitec Solutions</div>
              <p>Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">December 2011 - March 2013</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
            <div class="resume-content">
              <h3 class="mb-0">Junior Web Designer</h3>
              <div class="subheading mb-3">Shout! Media Productions</div>
              <p>Podcasting operational change management inside of workflows to establish a framework. Taking seamless key performance indicators offline to maximise the long tail. Keeping your eye on the ball while performing a deep dive on the start-up mentality to derive convergence on cross-platform integration.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">July 2010 - December 2011</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
            <div class="resume-content">
              <h3 class="mb-0">Web Design Intern</h3>
              <div class="subheading mb-3">Shout! Media Productions</div>
              <p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">September 2008 - June 2010</span>
            </div>
          </div>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="education">
        <div class="w-100">
          <h2 class="mb-5">Education</h2>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
            <div class="resume-content">
              <h3 class="mb-0">University of Colorado Boulder</h3>
              <div class="subheading mb-3">Bachelor of Science</div>
              <div>Computer Science - Web Development Track</div>
              <p>GPA: 3.23</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">August 2006 - May 2010</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row justify-content-between">
            <div class="resume-content">
              <h3 class="mb-0">James Buchanan High School</h3>
              <div class="subheading mb-3">Technology Magnet Program</div>
              <p>GPA: 3.56</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">August 2002 - May 2006</span>
            </div>
          </div>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="skills">
        <div class="w-100">
          <h2 class="mb-5">Skills</h2>

          <div class="subheading mb-3">Programming Languages &amp; Tools</div>
          <ul class="list-inline dev-icons">
            <li class="list-inline-item">
              <i class="fab fa-html5"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-css3-alt"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-js-square"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-angular"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-react"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-node-js"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-sass"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-less"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-wordpress"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-gulp"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-grunt"></i>
            </li>
            <li class="list-inline-item">
              <i class="fab fa-npm"></i>
            </li>
          </ul>

          <div class="subheading mb-3">Workflow</div>
          <ul class="fa-ul mb-0">
            <li>
              <i class="fa-li fa fa-check"></i>
              Mobile-First, Responsive Design
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Cross Browser Testing &amp; Debugging
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Cross Functional Teams
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Agile Development &amp; Scrum
            </li>
          </ul>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="interests">
        <div class="w-100">
          <h2 class="mb-5">Interests</h2>
          <p>Apart from being a web developer, I enjoy most of my time being outdoors. In the winter, I am an avid skier and novice ice climber. During the warmer months here in Colorado, I enjoy mountain biking, free climbing, and kayaking.</p>
          <p
            class="mb-0"
          >When forced indoors, I follow a number of sci-fi and fantasy genre movies and television shows, I am an aspiring chef, and I spend a large amount of my free time exploring the latest technology advancements in the front-end web development world.</p>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="awards">
        <div class="w-100">
          <h2 class="mb-5">Awards &amp; Certifications</h2>
          <ul class="fa-ul mb-0">
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>Google Analytics Certified Developer
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>Mobile Web Specialist - Google Certification
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>1
              <sup>st</sup>
              Place - University of Colorado Boulder - Emerging Tech Competition 2009
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>1
              <sup>st</sup>
              Place - University of Colorado Boulder - Adobe Creative Jam 2008 (UI Design Category)
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>2
              <sup>nd</sup>
              Place - University of Colorado Boulder - Emerging Tech Competition 2008
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>1
              <sup>st</sup>
              Place - James Buchanan High School - Hackathon 2006
            </li>
            <li>
              <font-awesome class="fa-li text-warning" :icon="['fas', 'trophy']"/>3
              <sup>rd</sup>
              Place - James Buchanan High School - Hackathon 2005
            </li>
          </ul>
        </div>
      </section>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Gridsome starter bootstrap"
  }
};
</script>

<style>
.subheading {
  text-transform: uppercase;
  font-weight: 500;
  font-family: "Saira Extra Condensed", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-size: 1.5rem;
}

.fa-li {
}

.social-icons a {
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: #495057;
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: #bd5d38;
}

.dev-icons {
  font-size: 3rem;
}

.dev-icons .list-inline-item i:hover {
  color: #bd5d38;
}

#sideNav .navbar-nav .nav-item .nav-link {
  font-weight: 800;
  letter-spacing: 0.05rem;
  text-transform: uppercase;
}

#sideNav .navbar-toggler:focus {
  outline-color: #d48a6e;
}

@media (min-width: 992px) {
  #sideNav {
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 17rem;
    height: 100vh;
  }
  #sideNav .navbar-brand {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin: auto auto 0;
    padding: 0.5rem;
  }
  #sideNav .navbar-brand .img-profile {
    max-width: 10rem;
    max-height: 10rem;
    border: 0.5rem solid rgba(255, 255, 255, 0.2);
  }
  #sideNav .navbar-collapse {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-box-flex: 0;
    -ms-flex-positive: 0;
    flex-grow: 0;
    width: 100%;
    margin-bottom: auto;
  }
  #sideNav .navbar-collapse .navbar-nav {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 100%;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item {
    display: block;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item .nav-link {
    display: block;
  }
}

section.resume-section {
  padding-top: 5rem !important;
  padding-bottom: 5rem !important;
  max-width: 75rem;
}

section.resume-section .resume-item .resume-date {
  min-width: none;
}

@media (min-width: 768px) {
  section.resume-section {
    min-height: 100vh;
  }
  section.resume-section .resume-item .resume-date {
    min-width: 18rem;
  }
}

@media (min-width: 992px) {
  section.resume-section {
    padding-top: 3rem !important;
    padding-bottom: 3rem !important;
  }
}

.bg-primary {
  background-color: #bd5d38 !important;
}

.text-primary {
  color: #bd5d38 !important;
}

a {
  color: #bd5d38;
}

a:hover,
a:focus,
a:active {
  color: #824027;
}
</style>
