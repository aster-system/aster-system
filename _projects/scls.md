---
description: SCLS is a little C++ librairie allowing its user to do some datas manipulations, almost as easily as in Python.
layout: project
location: ".."
main_title: SCLS
scls_foundation_version: "0.1"
---
<section>
    <h2>Presentation</h2>
    <article>
        <h3>What is SCLS ?</h3>
        <div>
            SCLS, for "Simple C++ Libraries Set", is a sets of C++ library, which means to make C++ development <i>almost</i> as easy as in Python.<br>
            The main goal of the library is to be simply used, implemented, downloaded and reviewed.<br><br>
            It targets mainly beginners or even seniors who don't want to develop some very simples and general things.
            For the simplest parts, the part is only header-only. For the most advanced libraries, you will needs some others libraries.
        </div>
    </article>
    <article>
        <h3>What the ressources ?</h3>
        <div>
            SCLS uses some dependencies in the parts. Even if they are more detailed in each parts documentations, here a list of the used ressources, listed by type.<br><br>
            Here the used C++ libraries :<br>
            <li>Glad : a very practical C++ library to make OpenGL multi platform easily, see <a href="https://glad.dav1d.de/">this website</a> for more informations.</li>
            <li>GLFW : an usefull C++ OpenGL high-level Open Source library, see <a href="https://www.glfw.org/">this website</a> for more informations.</li>
            <li>GLM : a very usefull C++ library, to do some complex math easily, see <a href="https://glm.g-truc.net/0.9.8/index.html">this website</a> for more informations.</li>
            <li>ZLib : a cool Open Source C++ compression library, see <a href="https://www.zlib.net/">this website</a> for more informations.</li>
            Here the used softwares :<br>
            <li>Code::Blocks : a cool C++ Open Source IDE, see <a href="https://www.codeblocks.org/">this website</a> for more informations.</li>
            <li>GCC : one of the most used C++ Open Source compiler, see <a href="https://www.codeblocks.org/">this website</a> for more informations.</li>
            <li>Visual Studio Code : used to write the web pages and the documentation, see <a href="https://code.visualstudio.com/">this website</a> for more informations.</li>
            Here some usefull website to learn about used things in SCLS :<br>
        </div>
    </article>
</section>
<section>
    <h2>Content</h2>
    {% for item in site.data.scls_parts %}
    <article>
        <h3>{{item.name}}</h3>
        <div>
            {{item.description}}<br>
            The current version of SCLS Foundation is {{item.version}}.<br><br>
            To have more informations, see the <a href="{{item.link}}">{{item.name}}</a> page.
        </div>
    </article>
    {% endfor %}
</section>