<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
        <link rel="stylesheet" href="project1.css">
        <meta charset="utf-8">
        <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.4/dist/jquery.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

        <Style>
        .welcome{
            font-size:15px;
            color:black;
        }
        </Style>
    </head> 
    <body data-spy="scroll" data-target="#navbar-nav" data-offset="1">

        <form class="form-inline fixed-top" action="/action_page.php">What is your name?<input type ="text" class="form-control" placeholder="Your name" name="name"> </form>

        <nav class="col-sm-10 col-10" id="navbar-nav">

        <div id="links"  class="nav nav-pills flex-column fixed-top">
        <p style="color:rgb(6, 16, 196);padding-left:1%;font-size: 30px">Links</p>
        <ul>
            <li class="nav-item"><a class="nav-link active" href="#About">About Me</a></li>
            <li class="nav-item"><a class="nav-link active" href="#Education">Education</a></li>
            <li class="nav-item"><a class="nav-link active" href="#Work">Work</a></li>
            <li class="nav-item"><a class="nav-link active" href="#Programming">Programming</a></li>
            <li class="nav-item"><a class="nav-link active" href="#favoritet">What I watch</a></li>
            <li class="nav-item"><a class="nav-link active" href="#website">Online</a></li>
            <li class="nav-item"><a class="nav-link active" href="#project">Project</a></li>
        </ul>
        </div>
        </nav>
        <div id="main" class="col-sm-9 col-8">
        <div id="About">
        <h1>Avery Estevez</h1>
        <ul>
            <li>Major: Computer Science</li>
            <li>Year: senior</li>
            <img src="IMG_1641.JPG" class="rounded-circle">
        </ul>
        </div>

        <div id="Education">
            <h1>Education</h1>
            <span class="education">
                <h2>Middletown Highschool</h2>
                <p>In 2020 I had graduated from Middletown high school obtaining my regents diploma.</p>
                <h2>St. John's University</h2>
                <p>Currently on track to graduate from St. Johns at the end of the spring 2024 semester</p>
            <span>
        </div>

        <div id="Work">
            <h1>Work</h1>
            <ol>
                <li>PizzaHut - Crew Memeber, Shift Manager</li>
                <li>Skechers - Product specialist</li>
            </ol>
        </div>

        <div id="Programming">
            <h1>Programming</h1>
            <ol>
                <li>HTML and Css, in high school I was introduced to HTML and css and have basic knowledge with most of it being refreshed.</li>
                <li>Java, the more recent language that I had become more accustomed to and mostly use now.</li>
            </ol>
        </div>

        <div id="favoritet">
            <h1>My favorite things to watch</h1>
            <table class="table-hover">
                <tr>
                    <td>Favorite show</td>
                    <td>The office</td>
                    <td><iframe width="560" height="315" src="https://www.youtube.com/embed/WaaANll8h18?si=8pmfGuK89uh-_ZOU&amp;controls=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></td>
                </tr>
                <tr>
                    <td>Favorite movie</td>
                    <td>Toy Story</td>
                    <td><img src="https://m.media-amazon.com/images/M/MV5BMDU2ZWJlMjktMTRhMy00ZTA5LWEzNDgtYmNmZTEwZTViZWJkXkEyXkFqcGdeQXVyNDQ2OTk4MzI@._V1_.jpg"></td>
                </tr>
            </table>

        </div>

        <div id="website">
            <h1>Where I spend my time online</h1>
            <a href=“https://www.youtube.com” target="_blank" style="color:red; padding-left:5%";>Youtube</a>
            <p>here I will watch a lot of random videos, be it a gaming video, educational video, or some random guy camping.</p>
        </div>

        <div id="projects">
            <h1>Projects</h1>
            <ol>
                <li>Project 1, making a basic profile website</li>
                <li>        <div class="spinner-border text-muted"></div></li>
            </ol>
        </div>
    </div>
    </body>
</html>
