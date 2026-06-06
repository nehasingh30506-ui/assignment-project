
<!DOCTYPE html>
<html lang="en">
  <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title> WEB TECHNOLOGY ASSIGNMENT </title>
       <style>
         *{
              margin:0;
              padding:0;
              box-sizing: border-box;
              font-family: Arial,sans-serif;
            }
          body {
             margin: 0;
             padding: 0;
            }
        header {
            background-color: black;
            color: white;
            padding: 5px;
           
        }
        nav{
            height: 40px;
            width: 100%;
            display: flex;
            align-items: center;
             justify-content: space-between;
             padding: 0 20px;
        }
        .left {
            display: flex;
            align-items: center;
        }
        .logo {
            margin-right: 10px;
        }
        .nav-buttons {
            display: flex;
            gap: 10px;
        }
        .btn1{
            background-color:black;
            color: white;
            border-radius: 5px;
            border: 1px solid rgb(107, 102, 102);
            padding: 5px 10px;
            cursor: pointer;
        }
         .btn2{
            background-color:#6502fa;
            color:white;
            padding: 5px 10px;           
            cursor: pointer;
            border-radius: 5px;
            border: 1px solid rgb(107, 102, 102);
        }
        main {
            padding: 0px;
        }
        .one{
            background-color:rgb(225, 212, 250);
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 60px;
        }
        .content {
            width: 500px;
            display: flex;
            flex-direction: column;
            margin-top: 20px;
           
        }
        .content h2{
            font-size: 45px;
            margin-bottom: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .content input {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-top: 10px;
            
        }
        .two {
            display:grid;
            grid-template-columns:repeat(2,1fr);
            gap:40px;
            padding:60px;
        }
        .service {
           display: flex;
           align-items: flex-start;
           gap: 20px;
        }
        .service img {
            height:75px;
            width:75px;
        }
        .service h2 {
            font-size: 20px;
            margin-bottom: 15px;
            max-width: 350px;
        }
        .service p{
            max-width: 300px;
            line-height: 1.5;
            margin-bottom: 15px;
        }
        footer {
            background-color: black;
            color: white;
            padding: 60px 10px;
            display: flex;
            
        }
        .footer-sec {
            display:flex;
            flex-wrap: wrap;
            max-width: 1200px;
            margin: 0 auto;
           justify-content: space-between;
           gap: 60px;
            
        }
            .footer-content {
                flex: 1;
                min-width: 180px;
                margin-bottom: 20px;

            }
            .footer-content h3 {
                font-size: 28px;
                margin-bottom: 15px;
            }
            .footer-content ul{
                list-style-type: none;
                padding: 0;
                margin: 0;
            }
            .footer-content ul li {
                margin-bottom: 8px;
                max-width: 150px;
            }
            .copyright {
                display: flex;
                flex-direction: column;
                justify-content:flex-end;
                gap: 12px;
            }
        
            .copyright p {
                font-size: 14px;
            }
        </style>
    </head>
    <body>
       <header>
        <nav>
            <div  class="left">
              <img src="https://img.freepik.com/premium-vector/abstract-logo-panel_1137500-47.jpg?w=2000" class="logo" height="35"  width="35" style="border-radius: 35%;">
              <h1 style="font-size: 15px;"> Abstract  | Help Center</h1>
            </div >
            <div class="nav-buttons">
              <button class="btn1"> Submit a Request </button> 
              <button class="btn2"> Sign In </button>
            </div>   
        </nav> 
      </header > 
   <main>
    <section class="one">
        <div class="content">
           <h2> How can we help ?</h2>
           <input type="text" placeholder="search                                                                                                                 &#128269;">
        </div>
    </section>
    <section class="two">
    <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/abstract.png" > 
            <div >
                <h2> Branches </h2>
                <p> Abstract Branches lets you manage,
                    version, and document your designs in
                    one place.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
        <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/account.png" > 
            <div >
                <h2> Manage your Account </h2>
                <p> Configure your account settings, such as
                    your email, profile details,and password.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
        <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/projects.png" > 
            <div >
                <h2> Manage Organization,teams,and 
                    projects 
                </h2>
                <p> Use Abstract Oraganizations, teams, and 
                    projects to organize your people and work.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
        <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/billing.png" > 
            <div >
                <h2> Manage Billing </h2>
                <p> Change subscriptions and payment
                    details.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
        <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/authenticate.png" > 
            <div >
                <h2> Authentication to Abstract </h2>
                <p> Set up and configure SSO,SCIM,and 
                    Just-in-Time provisioning.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
        <article class="service">
            <img src="https://abstract-webpage.netlify.app/assets/images/support.png" > 
            <div >
                <h2> Abstract Support </h2>
                <p> Get in touch with a human.
                </p>
                <a href="#"> Learn More &#8594;</a>
            </div>
        </article>
    </section>
  </main>
    <footer>
      <div class="footer-sec">   
           <div class="footer-content">
             <h3>Abstract</h3>
             <ul>
             <li>Branches</li>
             </ul>
            </div>
    
            <div class="footer-content">
                <h3>Resources</h3>
                <ul>
                    <li>Blog</li>
                    <li>Help Center</li>
                    <li>Release Notes</li>
                    <li> Status</li>
                </ul>
            </div>

            <div class="footer-content">
               <h3>Community</h3>
               <ul>
                 <li>Twitter</li>
                 <li>LinkedIn</li>
                 <li>Facebook</li>
                 <li>Dribbble</li>
                 <li>Podcast</li>
                </ul>
            </div>

            <div class="footer-content">
              <h3>Company</h3>
              <ul>
                 <li> About Us</li>
                 <li> Company</li>
                 <li>Leagal</li>
              </ul>
              <h3>Contact Us</h3>
              <ul>
                 <li> info@abstract.com</li>
              </ul>
            </div>
            <div class="Copyright">
               <img src="https://img.freepik.com/premium-vector/abstract-logo-panel_1137500-47.jpg?w=2000" class="logo" height="32"  width="32" style="border-radius: 35%;">
              <p>© Copyright 2022 </p>
              <p>Abstract Studio Design, Inc. </p>
              <p> All rights reserved.</p>
            </div>
        </div>
    </footer> 
 </body>
</html>
