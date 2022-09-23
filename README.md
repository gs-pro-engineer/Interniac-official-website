<div align="center">
        <a href="https://www.python.org/downloads/release/python-394/">
            <img src="https://img.shields.io/badge/python-3.9.4-blue.svg" alt="Python 3.9.4" />
        </a>
        <a href="https://github.com/Interniac/interniac-website/releases/">
            <img src="https://img.shields.io/github/release/Interniac/interniac-website.svg" alt="1.0.1" />
        </a>
        <a href="https://github.com/Interniac/interniac-website/graphs/commit-activity">
            <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="yes" />
        </a>
        <a href="https://lgtm.com/projects/g/Interniac/interniac-website/context:python"><img alt="Language grade: Python" src="https://img.shields.io/lgtm/grade/python/g/Interniac/interniac-website.svg?logo=lgtm&logoWidth=18"/></a>
    </a>
</div>

<div align="center">
    <a href="https://codecov.io/gh/Interniac/interniac-website">
        <img src="https://codecov.io/gh/Interniac/interniac-website/branch/master/graph/badge.svg?token=AN189HSGXH"/>
    </a>
    <a href="https://www.interniac.org">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.interniac.org%2Fstats%2Fnum-students%2F">
    </a>
    <a href="https://www.interniac.org">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.interniac.org%2Fstats%2Fnum-employers%2F">
    </a>
    <a href="https://www.interniac.org">
        <img src="https://img.shields.io/badge/students%20hired-20%2B-green">
    </a>
</div>

<div align="left" style='margin-top: 5rem'>
    <b><h2>Purpose of Project</h2></b>
        Given how competitive University admissions are and how often the average University student changes majors due to career confusion, getting a high school internship is more valuable than ever before. However, pre-university work experience is difficult to come by and oftentimes opportunities are given to students who have strong networks (either through a parent or their school). Today, there is no platform through which high school students all over the country can find an internship on their own. We aim to build a platform that supports high schoolers attending public schools and empowers businesses in hiring bright students. Interniac fills the gap in our education system by simplifying the process for employers to start internship programs and source candidates who are eager to gain valuable out-of-the-classroom work experience. <br> <br>
        Our mission is to bring you opportunities, whether that be an internship or a chance to speak to professionals in the field you are interested in. We strive to help you build your future. Join our platform to learn more about what opportunities Interniac can offer you! 
</div>

<div align="left" style='margin-top: 5rem'>
    <b><h2>Installation Instructions</h2></b>
    <p style='font-size: 2px'><i>contact repo owner for env file</i></p>
    <p>Ensure you have the Redis CLI installed - <a href="https://redis.io/topics/quickstart">Mac/Linux</a>, <a href="https://redis.com/blog/redis-on-windows-10/">Windows</a> </p>
    <p>Ensure you have Make installed - <a href="https://ftp.gnu.org/gnu/make/">Mac/Linux</a>, <a href="http://gnuwin32.sourceforge.net/packages/make.htm">Windows</a> </p>
    <ol>
        <li><code>git clone https://github.com/Interniac/interniac-website.git </code></li>
        <li><code>cd interniac-website</code></li>
        <li><code>make init-venv</code></li>
        <li><code>source ./venv/bin/activate</code> (Mac/Linux)</li>
        <li><code>./venv/bin/activate.bat</code> (Windows)</li>
        <li><code>make install-reqs</code></li>
    </ol>
</div>

<div align="left" style='margin-top: 5rem'>
    <b><h2>Run Instructions</h2></b>
    <ol>
    <li><code>source ./venv/bin/activate</code> (Mac/Linux)</li>
        <li><code>./venv/bin/activate.bat</code> (Windows)</li>        <li><code>make redis</code></li>
        <li><code>make</code></li>
            </ol>
</div>

<div align="left" style='margin-top: 5rem'>
    <b><h2>Run Tests</h2></b>
    <ol>
        <li><code>source ./venv/bin/activate</code> (Mac/Linux)</li>
        <li><code>./venv/bin/activate.bat</code> (Windows)</li>
        <li><code>make redis</code></li>
        <li><code>make test</code></li>
            </ol>
</div>
