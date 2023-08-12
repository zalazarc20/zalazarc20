<style>
    .content-parent {
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        height: 100%;
        justify-content: space-between; 
        align-items: center;
        margin-bottom: 1rem;
    }

    .item {
        flex-basis: calc(50% - 10px);
        padding: 1px;
        box-sizing: border-box;
    }

    .item img{
        margin-right: 2rem;
    }

    @media (max-width: 770px) {
        .content-parent{
            justify-content: flex-start;
        }

        .content-parent img{
            width: 100%;
        }
    }

    @media (max-width: 468px) {
        .content-parent{
            flex-direction: column;
            align-items: center;
        }
        .item {
            flex-basis: 100%;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            flex-direction: column;
        }

        .item h2{
            text-align: left;
            width: 100%;
        }

        .item img{
            margin: auto;
            width: 300px;
        }
    }
</style>

<h2> Hi, I'm Carlos Zalazar! <img src="parrot.gif" width="50"></h2>

<div class="content-parent">

<ul>
    <li>👨‍💻 Passionate about backend and frontend development.</li>
    <li>🥂 Let's work together to make our dreams come true.</li>
    <li>🤓 More than 6 years of programming experience.</li>
</ul>

<img src="cat2.gif" width="250">
</div>

<div class="content-parent">

<div class="item">
    <h2>Skills</h2>
    <img align='left' src="cat.gif" width="140">
    
<ul class="list-portfolio">
    <li>👨‍💻 Node js, MongoDB, MySql</li>
    <li>⚙️ React, Vue</li>
    <li>👁️ Html, CSS, Javascript</li>
</ul>
</div>


<div class="item">
    <h2>Contact</h2>
    <img align='left' src="coco2.gif" width="140">
    
<ul class="list-portfolio">
    <li><a href="mailto:zalazarc20@gmail.com">My personal email</a></li>
    <li><a href="https://www.instagram.com/zalazarc20/">zalazarc20</a> on Instagram</li>
    <li><a href="https://discord.gg/wEWg6ANtq4">My Server of Discord</a></li>
</ul>
</div>

</div>

<h1 align='center'>⚡️<i>Stay awesome!</i>⚡️</h1>

<p align="center">Thank you for visiting my profile. I'm always open to new opportunities for collaboration and learning. If you want to discuss projects, exchange ideas, or simply chat about web development, feel free to reach out. Together, we can create impactful and creative solutions.</p>

<p align="center">
        <img src="https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg" alt="Github Stats" />
</p>