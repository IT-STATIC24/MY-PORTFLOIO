<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
    <title>Welcome to my Website</title>
  </head>
  <body>
    <nav>
      <div class="nav__bar">
        <a href="#"><span class="logo nav__logo">C</span> Carlo</a>
        <div class="nav__menu__btn" id="menu-btn">
          <i class="ri-menu-3-line"></i>
        </div>
      </div>
      <ul class="nav__links" id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#certificates">Certificates</a></li>
        <li><a href="OJT.EXP.html">Practicum</a></li>
        <li><a href="#contact" class="btn">Contact</a></li>

      </ul>
      <a href="#contact" class="btn btn__large">Contact</a>
    </nav>
    <header class="section__container header__container" id="home">
      <div class="header__image">
        <img src="assets/Header (3).jpg" alt="header" />
      </div>
      <div class="header__content">
        <div>
          <h1>Carlo<br />Web<br />Designer</h1>
        </div>
        <p class="section__description">
          I'm a dedicated web developer with a creative flair and a penchant for
          turning lines of code into captivating online experiences. My journey
          in the digital realm began years ago, and I've since honed my skills
          in front-end development.
        </p>
        <div class="header__btn">
          <button class="btn">Hire Me Now</button>
        </div>
      </div>
    </header>

    <section class="section__container about__container" id="about">
      <div class="about__image">
        <img src="assets/bg.png" alt="bg" class="about__bg-1" />
        <img src="assets/bg.png" alt="bg" class="about__bg-2" />
        <img src="assets/About.jpg" alt="about" class="about__img" />
      </div>
      <div class="about__content">
        <h2 class="section__header">Bit About Me</h2>
        <p class="section__description">
          I am an enthusiastic web developer with a strong creative instinct and the ability to bring ideas to life. 
          My venture into web development started with a deep interest in coding and design, 
          evolving into a profession where I seamlessly integrate aesthetics with practicality. 
          Emphasizing user experience and a continuous effort to remain informed about current industry advancements, 
          I am devoted to crafting web solutions that surpass expectations.
        </p>
        <div class="about__btn">
          <p class="services-price-text mb-0"><a class="custom-btn btn custom-link" href="AGBONG_CV (1).pdf"> DOWNLOAD CV</a></p>
        </div>
      </div>
    </section>

    <section class="section__container service__container" id="portfolio">
      <h2 class="section__header">Portfolio</h2>
      <p class="section__description">
        Explore a showcase of my diverse projects, demonstrating my skills in
        web development, design, datasets and beyond. Each project reflects my passion
        for creating impactful and innovative digital experiences.
      </p>
      <div class="service__grid">
        <div class="service__card">
          <img src="XAMPP.png" alt="portfolio" />
          <span><i class="ri-window-fill"></i></span>
          <h4>XAMPP</h4>
          <p>
            XAMPP is a cross-platform web server that is free and open-source. XAMPP is a short form for Cross-Platform, Apache, MySQL, PHP, and Perl. 
            XAMPP is a popular cross-platform web server that allows programmers to write and test their code on a local webserver.
          </p>
        </div>
        <div class="service__card">
          <img src="ANDROID STUDIO.jpg" alt="portfolio" />
          <span><i class="ri-store-line"></i></span>
          <h4>ANDROID STUDIO</h4>
          <p>
            Android Studio is the official Integrated Development Environment (IDE) for Android App development. It is a powerful tool that allows developers to build high-quality applications for the Android platform.
          </p>
        </div>
        <div class="service__card">
          <img src="/VSCODE.jpg" alt="portfolio" />
          <span><i class="ri-smartphone-line"></i></span>
          <h4>VS CODE</h4>
          <p>
            Visual Studio (VS) Code is an open-source code editor primarily used to correct and repair cloud and web applications coding errors. 
            VS Code is developed by Microsoft and supports the macOS, Linux, and Windows operating systems. VS Code’s tools can be used to enhance the functionality of any written code.
          </p>
        </div>
        <div class="service__card">
          <img src="SPARK AR.png" alt="portfolio" />
          <span><i class="ri-share-fill"></i></span>
          <h4>META SPARK AR</h4>
          <p>
            Spark AR is a Facebook studio tool that allows users to build their own virtual and augmented reality effects. 
            Facebook has been consistently adding features to the platform since its introduction in 2017.
          </p>
        </div>
        <div class="service__card">
          <img src="ROBOFLOW.jpg" alt="portfolio" />
          <span><i class="ri-seo-line"></i></span>
          <h4>ROBOFLOW</h4>
          <p>
            Roboflow is an end-to-end computer vision platform that simplifies the process of building computer vision models. 
            Whether you’re a seasoned developer or just starting out, Roboflow empowers you to create your own computer vision applications.
          </p>
        </div>
        <div class="service__card">
          <img src="PACKET TRACER.jpg" alt="portfolio" />
          <span><i class="ri-share-circle-line"></i></span>
          <h4>CISCO PACKET TRACER</h4>
          <p>
            Packet Tracer is a cross-platform visual simulation tool designed by Cisco Systems that allows users to create network topologies and imitate modern computer networks.
            The software allows users to simulate the configuration of Cisco routers and switches using a simulated command line interface.
          </p>
        </div>
      </div>
    </section>

    <section class="section__container certificates__container" id="certificates">
      <h2 class="section__header">Certificates</h2>
      <p class="section__description">
        Acquiring certificates not only underscores my commitment to ongoing education but also serves as tangible evidence of my proactive approach to advancing my skills and knowledge within the field. 
        These certifications represent the culmination of dedicated effort and demonstrate my readiness to tackle new challenges with confidence and expertise. Furthermore, they validate my proficiency in specific areas, bolstering 
        my credibility as a competent and capable professional in the eyes of employers, clients, and peers alike.
      </p>
      <div class="portfolio__grid">
        <div class="portfolio__card">
          <img src="assets/Certificate1.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate2.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate3.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate4.JPG" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate5.png" alt="portfolio" />
        </div>
        <div class="portfolio__card">
          <img src="assets/Certificate6.png" alt="portfolio" />
        </div>
      </div>
      <section class="section__container service__container" id="portfolio">
        <h2 class="section__header">PROJECTS</h2>
        <p class="section__description">
          During my college days we made a lot of fun in programming course experience such as database,system adminstration, web development, game development,virtual reality and augmented reality this will showcase the dedication of my hardwork.
        </p>
        <div class="service__grid">
          <div class="service__card">
            <img src="VR.png" alt="portfolio" />
            <span><i class="ri-window-fill"></i></span>
            <h4>VIRTUAL REALITY</h4>
            <p>
             This was our project in 2nd year college to create a visual reality website through the use of vs code studio and internet resources.
            </p>
          </div>
          <div class="service__card">
            <img src="EXTENSION.png" alt="portfolio" />
            <span><i class="ri-store-line"></i></span>
            <h4>GOOGLE EXTENSION</h4>
            <p>
              One of my favorite project i created such extension in google that determine what is your weight base on your height and it appears if you are normal, above normal or obese.
            </p>
          </div>
          <div class="service__card">
            <img src="SYSAD.png" alt="portfolio" />
            <span><i class="ri-smartphone-line"></i></span>
            <h4>VIRTUAL MACHINE</h4>
            <p>
              During my 3rd year our professor gave us a project that creates a multi user in the windows 10 OS using Virtual Box Machine.
            </p>
          </div>
          <div class="service__card">
            <img src="BLENDER.png" alt="portfolio" />
            <span><i class="ri-share-fill"></i></span>
            <h4>BLENDER</h4>
            <p>
              This was one of my highlight projects before i created a lion masterpiece using the Blender 3.4v and adding movements and music effect to make it more realistic.
            </p>
          </div>
          <div class="service__card">
            <img src="ROBO.png" alt="portfolio" />
            <span><i class="ri-seo-line"></i></span>
            <h4>DATASET</h4>
            <p>
              Our capstone project sample dataset that i has made of several weeks to finish it is quiet hard at the start because you need to track one by one the object which is the fruitfly to get the specified numbers in total and gathered all the data using computer vision Roboflow.
            </p>
          </div>
          <div class="service__card">
            <img src="SPARK.png" alt="portfolio" />
            <span><i class="ri-share-circle-line"></i></span>
            <h4>FACE AI</h4>
            <p>
              Face AI is a fun project to create because you need to create it from the scratch and make your own idea of filter using Meta Spark Studio or Spark AR, It allows to use when it comes to upload from facebook or messenger once the filter uploaded the user may use the filter created in Spark AR it also allows multiple user if they have a link to the project.
            </p>
          </div>
        </div>
    </section>
   </div>
   <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/0kbGjTCuckVdXYU2VfyaDe?utm_source=generator" right="50%" left="505" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy">center</iframe>   
  </div>
    <section class="section__container contact__container" id="contact">
      <div class="logo">🡹</div>
      <h2 class="section__header">Let's Talk With Me!</h2>
      <p class="section__description">
        An open invitation to connect, and exploring collaborative opportunities
        on my personal portfolio website.
      </p>
      <div class="contact__socials">
        <a href="https://www.facebook.com/carlo.agbong"><i class="ri-facebook-fill"></i></a>
        <a href="https://www.instagram.com/carloescobio/"><i class="ri-instagram-fill"></i></a>
        <a href="https://github.com/IT-STATIC22"><i class="ri-github-fill"></i></a>
        <a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox"><i class="ri-google-fill"></i></a>
        <a href="https://www.messenger.com/t/7301008556595030"><i class="ri-messenger-line"></i></a>
      </div>
    </section>
    <footer class="footer">
      Copyright © 2024 Web Design Mastery. All rights reserved.
    </footer>

    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="main.js"></script>
  </body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>MY OJT EXPERIENCE</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-wide w3-padding w3-card">
    <a href="#home" class="w3-bar-item w3-button"><b>MAIN</b> PAGE</a>
    <!-- Float links to the right. Hide them on small screens -->
    <div class="w3-right w3-hide-small">
      <a href="#it profession" class="w3-bar-item w3-button">IT PROFESSION</a>
      <a href="#ojt experience" class="w3-bar-item w3-button">OJT EXPERIENCE</a>
      <a href="#personal qualities developed" class="w3-bar-item w3-button">PERSONAL QUALITIES DEVELOP</a>
      <a href="#thinking skills" class="w3-bar-item w3-button">THINKING SKILLS</a>
      <a href="#working experience" class="w3-bar-item w3-button">WORKING EXPERIENCE</a>
      <a href="index.html" class="w3-bar-item w3-button">PORTFOLIO</a>
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1500px;" id="home">
  <img class="w3-image" src="/A.jpg" alt="Architecture" width="1500" height="800">
  <div class="w3-display-middle w3-margin-top w3-center">
    <h1 class="w3-xxlarge w3-text-white"><span class="w3-padding w3-black w3-opacity-min"><b>OJT</b></span> <span class="w3-hide-small w3-text-light-grey">EXPERIENCE</span></h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content w3-padding" style="max-width:1564px">
  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/H (2).jpg" alt="John" style="width:100%">
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/J.jpg" alt="Jane" style="width:100%">
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/K.jpg" alt="Mike" style="width:100%">
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/L.jpg" alt="Dan" style="width:100%">
    </div>
  </div>
  <!-- Project Section -->
  <div class="w3-container w3-padding-32" id="projects">
    <b><h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">ABOUT ME</h3></b>
    <p>I am a unique individual with my own set of strengths, weaknesses, passions, and experiences. 
      I may have certain personality traits, such as being analytical, creative, empathetic, ambitious, or curious.
      Studied a degree of Bachelor of Science in Information Technology at Jose Maria College Foundation Inc, 
      and in the future i want to become successful in IT industry and living happily with my family in order to fullfill my wants and ambitions in life.
    </p>
  </div>
  <div class="w3-container w3-padding-32" id="about">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">What goals do I want to reach?</h3>
    <p>My IT goals may include mastering technical skills, obtaining certifications, advancing your career, 
      excelling in project management, specializing in niche areas, driving innovation, networking, maintaining work-life balance, 
      continuous learning, and contributing to the community. These goals vary depending on my role, interests, and career stage.
    </p>
  </div>
  <div class="w3-container w3-padding-32">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Who am I and who do I want to become?</h3>
    <p>As an IT professional, i am most certainly passionate about technology and problem solving. 
      I might currently work in IT as a front end developer, system administrator, data analyst, or to be part of networking area. 
      My goals could include becoming a skilled expert in your chosen niche, rising to higher levels of leadership and responsibility, contributing to 
      technological innovation within your organization or industry, and constantly learning and adapting to stay on the cutting edge of technological advancements.
    </p>
  </div>
  <div class="w3-container w3-padding-32">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Which skills do I possess?</h3>
    <p>As an IT professional,I possess a unique combination of technical and soft abilities required for success in the field. 
      My technical talents are likely to include knowledge of database administration, networking, and web development.Also thrive at problem solving, attention to detail, 
      communication, adaptability, project management, lifelong learning, customer service, analytical thinking, and teamwork. These abilities 
      to face challenging challenges, create new solutions, and effectively contribute to your organization's success in the ever-changing IT landscape.

    </p>
  </div>
  <div class="w3-container w3-padding-32">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Whom do I want to surround myself with?</h3>
    <p>I might Surrounding myself with a diverse network that includes mentors for guidance, 
      peers for collaboration, leaders for career advancement, subject matter experts for specialised knowledge, networking contacts for opportunities, 
      people with different perspectives for creativity, and supportive friends and family for balance and well-being. This network will give the support, learning opportunities, 
      and various viewpoints required for success in the IT sector.
    </p>
  </div>
  <div class="w3-container w3-padding-32">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Which companies do I want to work for?</h3>
    <p>As an IT professional, I'm likely to want to work for firms that share my values, provide possibilities for career advancement, 
      foster a stimulating work environment, and are at the forefront of technological innovation.
    </p>
  </div>
  <div class="w3-container w3-padding-32">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">What type of job do I want to do?</h3>
    <p>As an IT student, I have several job alternatives in the world of information technology. The front-end developer, systems administrator, 
      desktop support engineer, technical support and data analyst/scientist, are all potential roles. Consider my interests, talents, 
      and professional objectives to find the greatest fit. Gain some experience through my internships and apply all of the skills and knowledge that I have learned.
    </p>
  </div>
  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/LUCKY7.jpeg" alt="John" style="width:100%">
      <h3></h3>
      <p class="w3-opacity"></p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/TEAM.webp" alt="Jane" style="width:100%">
      <h3></h3>
      <p class="w3-opacity"></p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/BSIT (2).JPG" alt="Mike" style="width:100%">
      <h3></h3>
      <p class="w3-opacity"></p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="/MALAYAN.jpg" alt="Dan" style="width:80%">
      <h3></h3>
      <p class="w3-opacity"></p>
    </div>
  <!-- About Section -->
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">IT PROFESSION</h3>
    <p></div>
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16"> What is an IT profession for you?</h3>
    <p>For me, an IT job involves a wide range of roles and responsibilities centered on using technology to solve issues, optimize processes, 
      and drive innovation in a variety of disciplines. It entails planning, creating, implementing, and sustaining technological solutions that address the needs of individuals, corporations, and society as a whole. 
      IT professionals can specialize in a variety of areas, including software development, network administration, cybersecurity, data analysis, and IT consulting. 
      They are frequently entrusted for keeping up with the newest technological trends and breakthroughs, 
      diagnosing technical challenges, and working with cross-functional teams to reach corporate objectives.
  </div>
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Why do you think that your course is one of the most high-demand in the 
      society?</h3>
    <p>I believed that it is one of the highest demand course because of the combination of technological advancements, job opportunities, innovation,
       and societal impact makes IT courses among the most high-demand in society that makes us more updated in innovators in the future.
    </p>
  </div>
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Why do you choose BSIT course?</h3>
    <p>I chose a Bachelor of Science in Information Technology (BSIT) program because it provides learners with a path to understanding and engaging with
      technology's various applications. With a high demand for IT workers across industries, BSIT graduates have a wide range of job options and must constantly adapt to the field's changing nature through lifelong learning. BSIT students, who are equipped with problem-solving abilities and encouraged to think creatively, contribute to novel solutions to complicated problems. Furthermore, 
      pursuing a BSIT degree allows students to have a worldwide effect by tackling important societal challenges through technology-driven initiatives.
    </p>
  </div>
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">What will you become after finishing your course?</h3>
    <p>After i pursue this course i became an IT professionals with a degree that proves that nothing's gonna my dreams, moreover i want to get work instantly in the field of IT industry when i pursue this course and be independent indivdual buidling my own empire.
    </p>
  </div>
  <div class="w3-container w3-padding-32" id="it profession">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Describe a good IT professional.</h3>
    <p>A good IT professional combines technical knowledge, problem-solving talents, communication skills, ethical behavior, and a dedication to continual growth, allowing them to prosper in a dynamic and fast-paced field.
    </p>
  </div>
  <!-- Contact Section -->
  <div class="w3-container w3-padding-32" id="ojt experience">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">ON THE JOB TRAINING EXPERIENCE</h3>
    <div class="w3-container w3-padding-32" id="it profession">
      <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Explain why you planned this particular internship (OJT).</h3>
      <p>Choosing an internship in IT offers me a numerous benefits, including skill development, industry exposure, networking opportunities, resume enhancement, 
        engaging with people  learning organization culture, and personal growth. It provides hands-on experience, It helps me to explore career options, builds a professional network, 
        and enhances employability in the IT industry with the realtime scenario working with head in IT industry such as Senior IT and Project IT officer.
      </p>
    </div>
    <div class="w3-container w3-padding-32" id="it profession">
      <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Describe the organization, agency or OJT establishment.</h3>
      <p>My first impression in the company awesome cx organization is very well accomodated with their clients and very respectful making you feel comfortable to talk with the people inside the company, 
        The establishment is very well maintained clean the utility and the security are approachable also that keep us very calm when get entered into the building giving us a warm welcome. 
        There are times that i encountered also the agents in the company they are very kind and keen to us asking some random stuff that reminds us we are free and welcome in the industry to work along with them.
      </p>
    </div>
    <div class="w3-row-padding">
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/O (2).jpg" alt="John" style="width:100%">
        <h3></h3>
        <p class="w3-opacity">DELTA BUILDING</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/P (2).jpg" alt="Jane" style="width:100%">
        <h3></h3>
        <p class="w3-opacity">MTS BUILDING ENTRANCE</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/O.jpg" alt="Mike" style="width:100%">
        <h3></h3>
        <p class="w3-opacity">PRODUCTION FLOOR</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/N (2).jpg" alt="Dan" style="width:100%">
        <h3></h3>
        <p class="w3-opacity">RECHUB</p>
      </div>
    </div>
    <div class="w3-container w3-padding-32" id="it profession">
      <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Describe the job or duties.</h3>
      <p></p>
    </div>
    <div class="w3-row-padding">
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/F.jpg" alt="John" style="width:100%">
        <h3>UPGRADING RAM</h3>
        <p class="w3-opacity">GROUND FLOOR</p>
        <p>One of my task is to upgrade ram and check the motherboards of the laptop.</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/G.jpg" alt="Jane" style="width:100%">
        <h3>AUDTING MONITORS</h3>
        <p class="w3-opacity">3RD FLOOR</p>
        <p>Auditing monitors when it is defective or working this is part of the inventory side also</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/H1.jpg" alt="Mike" style="width:100%">
        <h3>RETAGGING ASSETS</h3>
        <p class="w3-opacity">4TH FLOOR</p>
        <p>Retagging assets to determine where it be deployed and monitored by our senior IT</p>
      </div>
      <div class="w3-col l3 m6 w3-margin-bottom">
        <img src="/I.jpg" alt="Dan" style="width:100%">
        <h3>AUDITING EQUIPMENTS</h3>
        <p class="w3-opacity">5TH FLOOR</p>
        <p>Auditing equipments when it is working or not we separate the defective and working equipments.</p>
      </div>
    </div>
    <div class="w3-container w3-padding-32" id="it profession">
      <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Importance of On-the-Job Training in your course</h3>
      <p>On-the-job training (OJT) is critical in IT education because it gives students with practical experience, skill development, 
        exposure to industry practices, and problem-solving ability. It also promotes professional networking, adaptability, 
        and soft skills that are necessary for success in the IT business. Finally, OJT bridges the gap between academic learning and professional preparedness, 
        developing well-rounded IT professionals capable of thriving in dynamic environments.
      </p>
    </div>
  <div class="w3-container w3-padding-32" id="personal qualities developed">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">PERSONAL QUALITIES DEVELOPED</h3>
        <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">My Personality Qualities Developed during my OJT Experience in AWESOME CX</h3>
        <p>Responsibility: Managed tasks diligently when my IT senior ask to do so.
        </p>
        <p>Self-Confidence: Successfully tackled challenges.
        </p>
        <p>Social Skills: Communicated effectively with colleagues and agents.
        </p>
        <p>Honesty and Integrity: Upheld ethical standards in all tasks.
        </p>
        <p>Adaptability and Flexibility: Adjusted to changing project demands when there has changed depending on the task i can assist easily.
        </p>
        <p>Team Player: Collaborated effectively within teams together with my co-interns from other school.
        </p>
        <p>Punctuality and Efficiency: Met deadlines consistently.
        </p>
        <p>Self-Direction: Took initiative in managing tasks that has given to me.
        </p>
        <p>Positive Attitude: Maintained optimism even in challenging situations.
        </p>
        <p>Professional Appearance: Presented oneself professionally specially in a work ethic.
        </p>
        <p>Cooperation: Worked well with others, respecting diverse opinions.
        </p>
        <p>Self-Motivation: Actively sought opportunities for growth and motivated with senior IT in the industry.
        </p>
        <p>Time Management: Prioritized tasks and met deadlines consistently.
        </p>
      </div>
    <div class="w3-container w3-padding-32" id="thinking skills">
      <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">THINKING SKILLS</h3>
          <p>
            In my IT journey, I've consistently acquired new technological knowledge, utilized logical reasoning to solve intricate issues, 
            demonstrated creativity in devising inventive solutions, exercised informed decision-making as a project manager, 
            and applied problem-solving abilities to overcome technical hurdles. These experiences have bolstered my competencies in learning, reasoning, creative thinking, decision-making, 
            and problem-solving, all essential for thriving in the IT domain and pertinent to my coursework.
          </p>
        </div>
      <div class="w3-container w3-padding-32" id="working experience">
        <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">WORKING EXPERIENCE</h3>
            <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">What do you do daily in the OJT establishment? How does it help in improving your 
              skills in your course</h3>
            <p>I consistently seek out tasks to undertake and regularly check in with supervisors to see if there are additional responsibilities I can assist with, such as aiding agents, conducting audits, and tagging equipment. 
              I firmly believe that this proactive approach enhances my skills in my field of study by reinforcing essential knowledge that an IT professional should possess.
              </p>
            </p>
      </div>
      <div class="w3-container w3-padding-32" id="working experience">
            <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Describe scenarios/situations and problems encountered during your work and how 
              you handle them</h3>
            <p>
            One of the hardest part that i encountered in internship is when i assign in graveyard shift because sometimes i felt sleepy but in honor to do my task i will give the best as i can to assist our IT seniors such as helping the agents and likely we do is technical support. 
            </p>
      </div>
    <div class="w3-container w3-padding-32" id="working experience">
          <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Discuss your overall observation and professional relations with co-OJTs, employees 
            and supervisors in the company. What have you learned from them?</h3>
          <p>
            Throughout my journey at AWESOME CX, I've enjoyed constructive and cooperative relationships with my fellow interns, colleagues, and supervisors. 
            Interactions with my peers have been supportive, while engaging with employees has provided valuable insights into company culture and industry norms. 
            Supervisors have consistently offered clear guidance and mentorship, which has greatly contributed to my professional development. 
            Overall, these relationships have significantly enhanced my internship experience at the company.
          </p>
          <div class="w3-row-padding">
            <div class="w3-col l3 m6 w3-margin-bottom">
              <div class="w3-display-container">
                <div class="w3-display-topleft w3-black w3-padding">INSTALLING ANTI-VIRUS</div>
                <img src="/B.jpg" alt="House" style="width:99%">
                <p>Mostly at a time we need to install anti virus which is sophos.</p>
              </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
              <div class="w3-display-container">
                <div class="w3-display-topleft w3-black w3-padding">RESETTING</div>
                <img src="/D.jpg" alt="House" style="width:99%">
                <p>One of my task is to resset the laptop to upgrade it and re installing updates.</p>
              </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
              <div class="w3-display-container">
                <div class="w3-display-topleft w3-black w3-padding">FIXING RAM</div>
                <img src="C.jpg" alt="House" style="width:99%">
                <p>Some of the laptops cannot work properly when the ram is not upgraded to enhance the hardware of equipments it is needed to upgrade it into 16gb RAM.</p>
              </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
              <div class="w3-display-container">
                <div class="w3-display-topleft w3-black w3-padding">DESKTOP SUPPORT</div>
                <img src="E.jpg" alt="House" style="width:99%">
                <p>Desktop Support is one of vulnerable task that we do when our IT seniors need an assistant to fix agents components such as Laptop,headset,keyboard,mouse,lan cable,etc.</p>
              </div>
            </div><div class="w3-row-padding">
              <div class="w3-col l3 m6 w3-margin-bottom">
                <img src="/a6.jpg" alt="John" style="width:100%">
                <h3>UPGRADING TO WINDOWS 11 PRO</h3>
              </div>
              <div class="w3-col l3 m6 w3-margin-bottom">
                <img src="/a7.jpg" alt="Jane" style="width:100%">
                <h3>CHECKING ACTIVE DIRECTORY/LOCAL HOST ACCOUNTS</h3>
              </div>
              <div class="w3-col l3 m6 w3-margin-bottom">
                <img src="/a8.jpg" alt="Mike" style="width:100%">
                <h3>ASSISTING SENIOR IT</h3>
              </div>
              <div class="w3-col l3 m6 w3-margin-bottom">
                <img src="/a10.jpg" alt="Dan" style="width:100%">
                <h3>AUDIT LAPTOP CONDITION</h3>
              </div>
            </div>
          </div>


<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by @VS CODE<a href="https://www.w3schools.com/w3css/default.asp" title="CARLO ESCOBIO AGBONG" target="_blank" class="w3-hover-text-green"></a></p>
</footer>

</body>
</html>

