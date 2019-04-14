<style>
body {
    width: 50%;
    margin: auto;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}

div>h2, h4, h6 {
    margin: 2%;
}

.center {
    text-align: center;
}

.section .title {
    display: flex;
}

hr {
    color: black;
}

.date {
    color: #555;
    text-align: right;
    width: 50%;
}

.label {
    font-weight: bold;
}

.position {
    width: 100%;
    display: flex;
}

.position div:first-child {
    width: 60%;
}
.position div:first span {
    margin: auto;
}

ul {
    margin-top: 0;
}

ul.positions {
    list-style-type: none;
    display: block;
    padding-left: 1%;
}
ul.positions > li {
    margin-top: 1%;
}

.title {
    font-size: .8em;
    font-weight: bold;
    position: relative;
    color: #008598;
    text-align: right;
}

.title:after {
    display: inline-block;
    content: "";
    height: 1px;
    background: #008598;
    position: absolute;
    width: 100%;
    top: 50%;
    margin-left: 15%;

}

.info span:first-child {
    width: 50%;
}

.tag {
    color: #008598;
}

b {
    color: #008598;/*#0096a9;*/
}

.section {
    width: 100%;
}

@media print {
    body {
        width: 100%;
    }
}

hr {
    margin: 0!important;
}

header h2 {
    margin-bottom: 0!important;
    text-align: center;
}

#flex {
    display: flex;
    width: 100%;
}

#flex #left {
    text-align: left;
    float: left;
    width: 50%;
}

#flex #right {
    text-align: right;
    float: right;
    width: 50%;
}

main {
    line-height: 1.6
}

a {
    color: black!important;
}

h6 a {
    color: #5c5c5c!important;
}

#coverLetter, #aboutMe{
    font-size: 1.1em;
}

dt, dd {
    margin-top: 0!important;
    margin-bottom: 0!important;
}

.standalone:after {
    display: none!important;
}
</style>

<div id="resume">
    <h2 class="center">Philip Dumaresq</h2>
    <h4 class="center tag">Passionate. Creative. Optimistic. Programmer.</h4>
    <h6 class="center">
        <a href="#">121 rue du Tartan, Gatineau QC, J9J 0W2</a> |
        <!-- <a href="github.com/nixin72">github.com/phdumaresq</a> | -->
        <a href="linkedin.com/in/phdumaresq">phdumaresq@gmail.com</a> |
        <a href="#">(613) 447-4889</a>
    </h6>
    <div class="section">
        <div class="title">Skills & Abilities</div>
        <ul>
            <li>
                <span class="label">Proficient Languages:</span>
                HTML, CSS, JavaScript, PHP, Java, C#, XML, SQL
            </li>
            <li>
                <span class="label">Other Languages:</span>
                Prolog, Lisp, C, Ruby, Python, LESS
            </li>
            <li>
                <span class="label">Frameworks:</span>
                Node.js, ASP.NET (MVC, Web Forms, Entity Framework), JUnit, jQuery, React.JS
            </li>
            <li>
                <span class="label">Tools:</span>
                Visual Studio/VS Code, IntelliJ, Eclipse, SQL Server, Vim, Jira, Confluence, GitHub
            </li>
            <li>
                <span class="label">Version Control:</span>
                Team Foundation Server, Git
            </li>
            <li>
                <span class="label">Other: </span>
                Agile Development, Scrum, System Analysis, Software/Database Architecture, Blackbox/Whitebox Testing
            </li>
            <li><b>Excellent communications skills</b> in English and working professional skill in French.</li>
        </ul>
    </div>
    <div class="section">
        <div class="title">Work Experience</div>
        <ul class="positions">
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">Full-Stack Developer</span>
                        <span>&vert;</span>
                        <span>TechInsights</span></div>
                    <div class="date">
                        May 2018 - August 2018
                    </div>
                </div>
                <div class="about">
                    <ul>
                        <li>Part of a <b>high-velocity agile development team</b>, working to deliver software quickly and reliably.</li>
                        <li>Worked under pressure from project owner and upper managment, always directly along the critical path.</li>
                        <li>Interacted daily with project stakeholders to build numerous frontend and backend applications.</li>
                        <li><b>Kick-started a project</b> to standardize development tools and procedures across the division.</li>
                        <li>Architected a new open-source node.js framework to replace our old PHP backend.</li>
                    </ul>
                </div>
            </li>
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">Teaching Assistant</span>
                        <span>&vert;</span>
                        <span>Heritage College</span></div>
                    <div class="date">
                        September 2017 - May 2018
                    </div>
                </div>
                <div class="about">
                    <ul>
                        <li>Helped students in a one-on-one environment learn the fundamentals of web design in HTML and CSS.</li>
                        <li>Taught OOP to students in their second semester, developing their core understanding of programming.</li>
                        <li>Worked hard to encouraged students when they were struggling, <b>helping them study even outside class time.</b></li>
                    </ul>
                </div>
            </li>
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">Computer Technician - Co-Op</span>
                        <span>&vert;</span>
                        <span>Heritage College</span></div>
                    <div class="date">
                        May 2016 - November 2016
                    </div>
                </div>
                <div class="about">
                    <ul>
                        <li>Started working as a co-op student, but continued part time with them during the school year.</li>
                        <li>My main responsibility was to help deploy and troubleshoot the school's migration to a virtual desktop environment.</li>
                        <li>To facilitate the workflow, I worked on an automation tool for imaging, helping increase everyone's productivity.</li>
                        <li><b>Worked from remote desktop into Windows servers</b> so I could control access directory and various distributed tools.</li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
    <div class="section">
        <div class="title">Education</div>
        <ul class="positions">
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">Bachelor of Computer Science - Co-Op</span>
                        <span>&vert;</span>
                        <span>Concordia University</span>
                    </div>
                    <div class="date">
                        In Progress
                    </div>
                </div>
            </li>
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">DEC - Computer Science Co-Op</span>
                        <span>|</span>
                        <span>Heritage College</span>
                    </div>
                    <div class="date">
                        2015-2018
                    </div>
                </div>
                <div class="about">
                    <ul>
                        <li><b>Graduated on honour roll.</b></li>
                        <li>Student Representative for 2017-2018</li>
                        <li><b>Represented the department</b> at a number of events, speaking to anyone from curious high schoolers to potential industry parteners.</li>
                    </ul>
                </div>
            </li>
            <li>
                <div class="position">
                    <div class="info">
                        <span class="label">High School Diploma</span>
                        <span>|</span>
                        <span>D'Arcy McGee High School</span>
                    </div>
                    <div class="date">
                        2012-2015
                    </div>
                </div>
            </li>
        </ul>
    </div>
    <div class="section">
        <div class="title">Achievements:</div>
        <ul>
            <li>
                <span class="label">FreeCodeCamp JAMStack Online Hackathon</span>
                <ul>
                    <li>Came <b>3rd place globally</b> and won <b>2 sponsor prizes.</b></li>
                </ul>
            </li>
        </ul>
    </div>
    <div class="section">
        <div class="title">Projects: </div>
        <dl>
            <dt>Project-Icarus</dt>
                <dd>This is a Lisp compiler I've been working on to learn how they work. It's purely educational, but my goal is to have it usable.</dd>
            <dt>Project-Horus</dt>
                <dd>A JavaScript web development framework in early stages of moving towards language-agnostic usage.<dd>
            <dt>LeDocubot</dt>
                <dd>An auto-documentation tool that integrates into GitHub to help document your JavaScript or TypeScript code on push.</dd>
        </dl>
    </div>
    <div class="section">
        <div class="title standalone">References:  available upon request</div>
    </div>
</div>
