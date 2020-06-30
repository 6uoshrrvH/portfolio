<template>
  <div id="app">

    <navigation>
      <a href="mailto:harrysong066@gmail.com" class="link is-hidden-mobile" target="_blank">harrysong066@gmail.com</a>
      <a href="//www.linkedin.com/in/harrysong066" class="link is-hidden-mobile" target="_blank">LinkedIn</a>
      <a href="//github.com/6uoshrrvH" class="link is-hidden-mobile" target="_blank">GitHub</a>
      <a href="#contact" class="link">Contact Me</a>
    </navigation>

    <hero-section>
      Hi, my name is <strong>Harry</strong>.<br class="is-hidden-mobile" />
      I’m a <strong>freelance UI developer</strong>.<br class="is-hidden-mobile" />
      I make <strong>web</strong> and <strong>mobile</strong> apps with <strong>Angular</strong>.
    </hero-section>

    <!-- About section -->

    <content-section>
      <content-columns>

        <!-- Biography -->
        <content-column>
          <profile location="Thomas Ave W, St Paul, MN 55104" />
          <p>
            Over the past decade, I've honed a passion for technology into a diverse set of web & mobile development-related skills.
            <br /><br />
            I typically work on web-based applications, both mobile and desktop, architect workflows and interfaces, and helping implement these concepts in code. Even so, I'm open to new experiences and love exploring new technologies and industries.
            <br /><br />
            When I'm not working on side-projects or attending game-jams and hack-a-thons, I enjoy exploring the city on bicycle, mixing new and unusual cocktails, or taking it easy around the house with my cats.
          </p>
        </content-column>

        <!-- Skills -->
        <content-column>
          <skill-set :skills="[
            [ 'Angular', 'web', 'Angular' ],
            [ 'TypeScript', ['web', 'api'], 'TypeScript' ],
            [ 'C#', 'api', 'CSharp' ],
            [ 'Ionic', 'mobile', 'Ionic' ],
            [ 'JavaScript', ['web', 'api'], 'JavaScript' ],
            [ 'NodeJS', 'api', 'NodeJS' ],
            [ 'NativeScript', 'mobile', 'NativeScript' ],
            [ 'Cordova', ['web', 'mobile'], 'Cordova' ],
            [ 'HTML5', 'web', 'HTML5' ],
            [ 'CSS3', 'web', 'CSS' ],
            [ 'D3.js', ['web', 'visual'], 'D3' ],
            [ 'Highcharts', ['web', 'visual'], 'HighCharts' ],
            [ 'RxJS', 'web', 'RxJS' ],
            [ 'SASS', 'web', 'SASS' ],
            [ 'Jest', [ 'test', 'web', 'api' ], 'Jest' ],
            [ 'Mocha', [ 'test', 'web', 'api' ], 'Mocha' ]
          ]" />
        </content-column>

      </content-columns>
    </content-section>

    <section-title>EDUCATION</section-title>

    <content-section>
      <job-timeline>
        <job title="Software Technology Institute of Dalian Jiaotong University" company="Master's degree, Computer Engineering">
        </job>
      </job-timeline>
      <job-timeline>
        <job title="Wuhan University of Technology" company="Bachelor of Science - BS, Computer and Information Sciences and Support Services">
        </job>
      </job-timeline>
    </content-section>

    <section-title>EXPERIENCE</section-title>

    <content-section>
      <job-timeline>
        <job title="Freelance Angular Developer" company="Self-Employed">
          ● Worked on AngularJS, Angular 2+, JavaScript, and TypeScript projects with various clients around the world.<br>
          ● Communicated and collaborated with international teams and companies to get the business requirements into reality.<br>
          ● Followed the SOLID design principle to build the best quality software and codebase.<br>
          ● Used various tools and libraries for web development such as Azure DevOps, JIRA, GitHub, MS Teams, Slack, Skype, InvisionApp, and Zeplin.<br>
          ● Often acted as a DevOps engineer and I majored in CI/CD integration with the fully tested version of the software.<br>
        </job>
        <job title="Angular UI Developer" company="Illumina">
          ● Developed the front-end of the Angular 2 web application.<br>
          ● Integrated REST-ful API endpoints to the application using RxJS, Observables, Swagger, and Postman.<br>
          ● Translated mockups into working boilerplates, complete with responsiveness, animations, and functionality.<br>
          ● Built components libraries using Polymer, Angular Material Design, Bootstrap, HTML, and Sass/LESS/CSS.<br>
          ● Integrated Grunt to streamline the development workflow and allow for reusable components across different platforms.<br>
          ● Conducted usability studies that exposed convoluted workflows and inconsistencies and implemented the resulting recommendations<br>
        </job>
        <job title="JavaScript Developer" company="Caterpillar Inc">
          ● Joined a team writing an AngularJS web application replacing an excel spreadsheet "Value Added Sales Tool" (VAST). The application is used to compare costs for engines and allow detailed analysis of expenses and total cost of ownership.<br>
          ● Created a complex user interface for preparing engine cost studies, with the ability to copy/paste large data-sets.<br>
          ● Build the back-end to support the efficient storage of the relevant data in SQL Server. Designed table structure, indexes, and ORM based data layer to support the application.<br>
          ● Contributed to the DevOps approach to source control including automated testing, gated check-ins, automated build/deploy.<br>
          ● Set up Azure resources including App Service, Azure SQL, Application Insights, KeyVault.<br>
        </job>
        <job title="Frontend Developer" company="Koch Industries Inc">
          ● Worked as the frontend developer and participated in dozens of projects, large and small, over 6 years.<br>
          ● Leveraged the latest AngularJS, JavaScript technologies on a wide variety of projects for the refineries.<br>
          ● Provided technical expertise in a wide variety of areas including new hire/contractor mentoring, new technology research, prototyping, and capability development.<br>
          ● Led an effort to leverage agile methodology in our organization, went to training, and helped roll out a process for the department.<br>
          ● Administered Team System (TFS) for our department. I installed the new instance, executed a plan to move our codebase into the new source control, and implemented a workflow leveraging work items.<br>
        </job>
      </job-timeline>
    </content-section>

    <section-title>PROJECTS</section-title>

    <content-section>
      <project title="Capstone Logistics" category="Logisitcs, Supply Chain, Front-End">
        <template slot="pictures">
          <img :src="require('./assets/Capstone.png')" alt="Animeta logo." />
        </template>
        <template slot="description">
          This platform was designed for Capstone partners to manage their POs, Appointments, and other logistics and supply chain workflows.
          <br /><br />
          The project was started with Angular 6 and upgraded to Angular 7 and then 8 later.
          <br /><br />
        </template>
        <template slot="tools-used">
          <li>Angular 8</li>
          <li>D3.js</li>
          <li>Rxjs</li>
          <li>Material Design</li>
          <li>Angular CDK</li>
          <li>Semantic UI</li>
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>PostgreSQL</li>
          <li>GraphQL</li>
          <li>Node.js</li>
          <li>.Net Core</li>
          <li>ODBC</li>
          <li>MSSQL</li>
          <li>Entity Framework</li>
        </template>
        <template slot="subtitle">
          <a class="link" href="//qa-mr.capstonelogistics.com/" target="_blank">Visit Webapp</a>
        </template>
      </project>
    </content-section>

    <content-section>
      <project title="ClubHouse" category="Front-End Development, Project Management, Agile">
        <template slot="pictures">
          <img :src="require('./assets/ClubHouse.png')" alt="ClubHouse" />
        </template>
        <template slot="description">
          Clubhouse is the collaborative home for software development that makes it easier and more enjoyable to plan and build with your teams, wherever you are.
          <br /><br />
          Optimized for speed, Clubhouse is fast to load, incredibly quick to configure and navigate, all so you have more time every day to create.
          <br /><br />
        </template>
        <template slot="tools-used">
          <li>TypeScript</li>
          <li>Angular 7</li>
          <li>Angular Universal</li>
          <li>Angular CDK</li>
          <li>JavaScript</li>
          <li>HighCharts</li>
          <li>SASS/CSS</li>
          <li>Ngrx</li>
          <li>Rxjs</li>
          <li>Amazon S3</li>
        </template>
        <template slot="subtitle">
          <a class="link" href="//clubhouse.io/" target="_blank">Visit Webapp</a>
        </template>
      </project>
    </content-section>

    <content-section>
      <project title="LendUp" category="Fintech, Full-Stack, SaaS">
        <template slot="pictures">
          <img :src="require('./assets/Lendup.png')" alt="LendUp" />
        </template>
        <template slot="description">
          LendUp is a mission-driven fintech company that puts people on a path to better financial health through accessible, quality credit products including short-term loans, credit cards (now a part of Mission Lane), and online education videos.
          <br /><br />
          LendUp offers credit cards, loans, free financial education, and, where available, the opportunity to build credit, right from your phone.
          <br /><br />
        </template>
        <template slot="tools-used">
          <li>AngularJS</li>
          <li>JavaScript</li>
          <li>Node.js</li>
          <li>Express.js</li>
          <li>MongoDB</li>
          <li>Stripe</li>
          <li>Babel</li>
          <li>Google Analytics</li>
          <li>Bootstrap 4</li>
          <li>jQuery</li>
          <li>CSS3</li>
          <li>HTML5</li>
          <li>API Integrations</li>
          <li>Lodash</li>
        </template>
        <template slot="subtitle">
          <a class="link" href="//www.lendup.com" target="_blank">Visit Webapp</a>
        </template>
      </project>
    </content-section>

    <content-section>
      <project title="PhotoMath" category="Hybrid Mobile App, Front-End Development">
        <template slot="pictures">
          <img :src="require('./assets/Math.jpg')" alt="Screenshots of PhotoMath." />
        </template>
        <template slot="description">
          Photomath is the #1 app to learn math, to take the frustration out of math and to bring more peace to your daily student life.
          <br /><br />
          Whether you are a mathlete or math challenged, Photomath will help you interpret problems with comprehensive math content from arithmetic to calculus to drive learning and understanding of fundamental math concepts.
          <br /><br />
        </template>
        <template slot="tools-used">
          <li>Ionic5</li>
          <li>Angular9</li>
          <li>TypeScript</li>
          <li>Ngrx</li>
          <li>Rxjs</li>
          <li>Cordova</li>
          <li>SASS/CSS</li>
        </template>
        <template slot="subtitle">
          <a class="link" href="//www.photomath.net" target="_blank">Visit Website</a>
        </template>
      </project>
    </content-section>

    <content-section>
      <project title="Gabbi" category="Mobile App, Front-End Development, Messaging, SMS">
        <template slot="pictures">
          <img :src="require('./assets/Gabbi.ai.png')" alt="Screenshots of Gabbi.ai." />
        </template>
        <template slot="description">
          Gabbi is a real-time messaging app for real-estate professionals. The
          hybrid mobile app, built with Ionic 3 and Cordova, gives agents a way to
          manage their clients using CRM-like features without having to manage
          a full-blown CRM.
          <br /><br />
          Backed by a machine-learning system, Gabbi is able to
          automatically notify the agent of important events as well as categorize,
          reply-to and follow-up with prospective and existing clients and leads.
          <br /><br />
        </template>
        <template slot="tools-used">
          <li>Ionic 3</li>
          <li>Angular 5</li>
          <li>TypeScript</li>
          <li>Twilio API Integration</li>
          <li>HTML5</li>
          <li>SASS/CSS</li>
          <li>Sketch</li>
          <li>Cordova</li>
        </template>
        <template slot="subtitle">
          <a class="link" href="//www.gabbi.ai" target="_blank">Visit Website</a>
        </template>
      </project>
    </content-section>

    <section-title>Contact Me</section-title>
    <a name="contact"></a>

    <content-section>
      <contact-form /><!-- TODO: form -->
    </content-section>

    <!-- Footer -->

    <page-footer />

  </div>
</template>

<script>
import ContactForm from './components/ContactForm.vue'
import ContentColumn from './components/ContentColumn.vue'
import ContentColumns from './components/ContentColumns.vue'
import ContentSection from './components/ContentSection.vue'
import HeroSection from './components/HeroSection.vue'
import Job from './components/Job.vue'
import JobTimeline from './components/JobTimeline.vue'
import Navigation from './components/Navigation.vue'
import PageFooter from './components/PageFooter.vue'
import Profile from './components/Profile.vue'
import Project from './components/Project.vue'
import SectionTitle from './components/SectionTitle.vue'
import SkillSet from './components/SkillSet.vue'

export default {
  name: 'App',

  provide () {
    return {
      app: this
    }
  },

  components: {
    ContactForm,
    ContentColumn,
    ContentColumns,
    ContentSection,
    HeroSection,
    Job,
    JobTimeline,
    Navigation,
    PageFooter,
    Profile,
    Project,
    SectionTitle,
    SkillSet
  },

  metaInfo: {
    title: 'Harry Song | Freelance Angular Developer', // set a title
    htmlAttrs: {
      lang: 'en'
    },
    meta: [
      { name: 'robots', content: 'index, follow' },
      { name: 'keywords', content: 'freelance, angular, angular developer, ui,ux,full-stack,full-stack developer,fullstack,front-end,frontend,angular,ionic,reactnative,react native,rxjs,vuejs,vue,reactjs,react,nodejs,typescript,javascript,app,mobile' },
      { name: 'description', content: 'The various works of Harry Song, Freelance Angular Developer.' },
    ]
  },

  data () {
    return {
      scrollPos: 0,
      scrollHandler: undefined
    }
  },

  created () {
    this.scrollHandler = this.scroll.bind(this)
    window.addEventListener('scroll', this.scrollHandler)
  },

  destroyed () {
    window.removeEventListener('scroll', this.scrollHandler)
  },

  methods: {
    scroll () {
      this.scrollPos = window.scrollY
    }
  }
}
</script>

<style lang="sass">
@import "@/styles/reset.sass"
@import "@/styles/styles.sass"
@import url("https://fonts.googleapis.com/css?family=Work+Sans:200,400,600")

#app
  font-family: 'Work Sans', 'Avenir', Helvetica, Arial, sans-serif

.is-hidden-mobile
  display: none
  +desktop
    display: inline-flex
</style>
