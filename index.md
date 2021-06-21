---
layout: default
title: Project
---

<h2> Projects </h2>

<br>
<hr>
<br>

<div class="row">
    <div class="col-sm-8" >
        <div class="container">
            <h3> 
                Fabflix 
            </h3>
            <p>
                Full Stack Web Application &middot; 
                <i>
                    UC Irvine, CS122B
                </i>
                <br>
                <small>
                    Apr 2021 - Jun 2021
                </small>
            </p>
            <p>
                Team: Individual Work
            </p>
            <p>
                This is an e-commerce movie shopping website(Not really selling things). The website contains separate logins for users and bployees. If users want to check out a movie, then the user must login first. The bployee dashboard is for adding more movies and stars into the database, and also the metadata of the database structure.
            </p>
            <p>
                The backend is written in <b>Java Servlet</b>, and the frontend is using <b>Javascript, HTML, CSS, and ajax</b> that's for calling the backend api. The database server used is <b>MySQL</b> and it's hosted in an AWS ec2 instance. The whole project is deployed on the <b>Tomcat</b> servers in both master and slave instances. For security reasons, <b>reCAPTCHA</b> is set up to prevent bots from checking out the products and <b>HTTPS</b> is enforced. For scalability, <b>Master/Slave replication, load balancer, and connection pooling</b> were used to increase the performance of the website.
            </p>
            <p>
                Website: 
                <a href="https://fabflix.shop">
                    https://fabflix.shop
                </a>
                <br>
                Software Tools: JavaServlets, MySQL, Apache Tomcat, AWS, GCP, Javascript, Java, UDF, HTTPS, JDBC, Ajax, Stored Procedures
            </p>
        </div>
    </div>
    <div class="col-sm-4">
            <a href="https://fabflix.shop">
                <img src="img/fabflix.png" alt="Fabflix Webpage">
            </a>
    </div>
</div>

<br>
<hr>
<br>

<div class="row">
    <div class="col-sm-8">
        <div class="container">
            <h3> 
                Let’s Fika 
            </h3>
            <p>
                Capstone Project &middot; 
                <i>
                    UC Irvine, CS180A/B
                </i>
                <br>
                <small>
                    Jan 2021 - Jun 2021
                </small>
            </p>
            <p>
                Team Members: Albert Zhang, Jack Su, Michael Wang
            </p>
            <p>
                This Capstone project is sponsored by a startup company that wants to provide a space for people to share perspectives during a Swedish coffee time, known as Fika. To escape from commenting and likes and provide a healthy and safe environment for people so that speakers are more encouraged to share.
            </p>
            <p>
                The technical structure of the project is the <b>MERN</b> stack development, which stands for <b>MongoDB, ExpressJS, React, and NodeJS.</b> Since most of the team is more familiar with python, we decided to use <b>Python Flask</b> for the backend in the beginning. However, the connecting of backend and frontend has an unresolved bug for two weeks, so we decided to convert the whole project into NodeJS for the backend. As everyone is working for a specific feature, the team is full-stack so everyone is more familiar with the project code. So, I learned React and NodeJS during this project. I am responsible for the content management for administrators and overall display control for the frontend. Since the content is hosted on Spotify and Youtube, I used <b>OAuth2.0</b> for both API calls for pulling content links into our database.
            </p>
            <p>
                Website: 
                <a href="https://letsfika.today/">
                    https://letsfika.today/ 
                </a>
                <br>
                Software Tools: MongoDB, ExpressJS, React, NodeJS, Netlify, Heroku, Youtube Data API, Spotify API
            </p>
        </div>
    </div>
    <div class="col-sm-4">
        <a href="https://letsfika.today/">
            <img src="img/letsfika.png" alt="Let's Fika Webpage">
        </a>
    </div>
</div>

<br>
<hr>
<br>

<div class="row">
    <div class="col-sm-8">
        <div class="container">
            <h3> 
                Pixel Jump 
            </h3>
            <p>
                Artificial Intelligence Project in Malmo &middot; 
                <i>
                    UC Irvine, CS175
                </i>
                <br>
                <small>
                    Oct 2020 - Dec 2020
                </small>
            </p>
            <p>
                Team Members: Hongen Lei, Wencong She
            </p>
            <p>
                Pixel Jump is a gameplay simulation in Malmo(Minecraft) where the agent will perform physical jumps from one platform to another with user-control jump simulation based on the <b> 3D projectile motion calculation</b>. The purpose of this project is to let the agent observe his surrounding platforms and then pick an initial velocity from a continuous action space to ensure that the agent can land on various positions of the next platform and hopefully jump onto the glass (goal) block for greater reward.
            </p>
            <p>
                This is <b>Deep Reinforcement Learning</b> project that uses <b>PPO(Proximal Policy Optimization).</b>The algorithm makes updates based on the transitions that were obtained by the current policy and is used in the agent’s decision for better performance. To scale up the performance of our agent, we made five difficult maps to train our agent for at least 24 hours. Data analysis can be found in the 
                <a href="https://bikaylee.github.io/Pixel-Jump/final.html">
                    final report
                </a>.
            </p>
            <p>
                Website: 
                <a href="https://bikaylee.github.io/Pixel-Jump/">
                    https://bikaylee.github.io/Pixel-Jump/
                </a>
                <br>
                Source Code: 
                <a href="https://github.com/bikaylee/Pixel-Jump">
                    https://github.com/bikaylee/Pixel-Jump
                </a>
                <br>
                Software Tools: gym, rllib, ppo, numpy
            </p>
        </div>
    </div>
    <div class="col-sm-4">
        <a href="https://bikaylee.github.io/Pixel-Jump/">
            <img src="img/pixeljump.gif" alt="Pixel Jump Webpage">
        </a>
    </div>
</div>

<br>
<hr>
<br>

<div class="row">
    <div class="col-sm-8">
        <div class="container">
            <h3> 
                Wumpus World 
            </h3>
            <p>
                Intro to Artificial Intelligence Project &middot; 
                <i>
                    UC Irvine, CS171
                </i>
                <br>
                <small>
                    Mar 2020
                </small>
            </p>
            <p>
                Team: Individual Work
            </p>
            <p>
                This project is from an intro course of Artificial Intelligence. The Wumpus World is classified as <b>single agent, partially observable, simulated, static, discrete, sequential, and deterministic.</b> The goal is to let the agent get as many points as possible. Given a 2D grid of tiles, the agent will be scored based on the performance of getting a gold safely. The objective is to use <b>a* search</b> to find the minimal step of path both in searching the target and returning. Based on the current perceptions to predict the safety of surrounding tiles, the agent will go to the safest location in searching and will be marked trapped and return to the starting point if surroundings are too dangerous.
            </p>
            <p>
                Software Tools: C++, a* search
            </p>
        </div>
    </div>
    <div class="col-sm-4">
            <img src="img/wumpusworld.png" alt="Wumpus World">
    </div>
</div>

<br>
<hr>
<br>

<div class="row">
    <div class="col-sm-8">
        <div class="container">
            <h3>
                She Who Codes 
            </h3>
            <p>
                Webpage &middot; 
                <i> 
                    CCSF - She Who Codes Club 
                </i> 
                <br>
                <small>
                    Sep 2018
                </small>
            </p>
            <p>
                Team: Individual Work
            </p>
            <p>
                As the treasurer of She Who Codes club in City College of San Francisco, I redesigned the club webpage to promote our club. The webpage contains past events and upcoming events. It also includes the club contact information, meeting time, and mission.
            </p>
            <p>
                Website: 
                <a href="https://bikaylee.github.io/She-Who-Codes/">
                    https://bikaylee.github.io/She-Who-Codes/
                </a>
                <br>
                Source Code: 
                <a href="https://github.com/bikaylee/She-Who-Codes">
                https://github.com/bikaylee/She-Who-Codes
                </a>
                <br>
                Software Tools: HTML, CSS, Javascript
            </p>
        </div>
    </div>
    <div class="col-sm-4">
        <a href="https://bikaylee.github.io/She-Who-Codes/">
            <img src="img/shewhocodes.png" alt="She Who Codes Webpage">
        </a>
    </div>
</div>

<br>
<hr>
<br>
<div class="row">
    <div class="col-sm-8">
        <div class="container">
            <h3> 
                La Fusion 
            </h3>
            <p>
                Webpage &middot; 
                <i>
                    San Francisco Code Ramp
                </i>  
                <br>
                <small>
                    Feb 2017 - Apr 2017
                </small>
            </p>
            <p>
            Team: Individual Work
            </p>
            <p>
                Very first webpage project after taking APCS in junior year of high school. At San Francisco Success Center, this 8-week course about web development fundamentals was taught by an experienced software engineer. This project is a redesigned website for a local restaurant in San Francisco.
            </p>
            <p>
                Website: 
                <a href="https://bikaylee.github.io/La-Fusion/">
                    https://bikaylee.github.io/La-Fusion/
                </a> 
                <br>
                Source Code: 
                <a href="https://github.com/bikaylee/La-Fusion">
                    https://github.com/bikaylee/La-Fusion
                </a>
                <br>
                Software Tools: HTML, CSS, Javascript
            </p>
        </div>
    </div>
    <div class="col-sm-4">
        <a href="https://bikaylee.github.io/La-Fusion/">
            <img src="img/lafusion.png" alt="La Fusion Webpage">
        </a>
    </div>
</div>

<br>
<hr>
