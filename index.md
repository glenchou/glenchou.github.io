---
layout: page
title: Glen Chou
---

<img align="right" src="images/glen.png" style="margin: -70px 0px 0px 20px; width: 285px;" >

<span style="font-weight:bold">Postdoctoral Associate, CSAIL</span><br>
<span style="font-weight:bold">Massachusetts Institute of Technology </span><br>
<span style="font-weight:bold">Office</span>: 32-380<br>
<span style="font-weight:bold">Email: </span>gchou [at] mit [dot] edu<br>
<span style="font-weight:bold"> <a href="cv_10_29_23.pdf"> CV</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;  </span>
<span style="font-weight:bold"><i class="ai ai-google-scholar-square ai-1x"></i> <a href="https://scholar.google.com/citations?user=90whi3wAAAAJ&hl">Scholar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;  </span>
<span style="font-weight:bold"><i class="ai ai-researchgate-square ai-1x"></i> <a href="https://www.researchgate.net/profile/Glen_Chou"> ResearchGate</a>  </span>

<br>
## About me:

<style>
    p {
        text-align: justify;
    }
</style>
<p>I was born and raised in Northern California. After earning dual B.S. degrees in Electrical Engineering and Computer Science and Mechanical Engineering from UC Berkeley in 2017, where I worked with <a href="https://people.eecs.berkeley.edu/~tomlin/">Claire Tomlin</a> and <a href="https://people.eecs.berkeley.edu/~anca/">Anca Dragan</a>, I left the eternal summer behind to receive an M.S. and Ph.D. in Electrical and Computer Engineering from the University of Michigan in 2019 and 2022, respectively. At Michigan, I was advised by <a href="http://web.eecs.umich.edu/~necmiye/">Necmiye Ozay</a> and <a href="http://web.eecs.umich.edu/~dmitryb/">Dmitry Berenson</a>. Currently, I am a postdoc at MIT CSAIL, where I work with <a href="http://groups.csail.mit.edu/locomotion/russt.html">Russ Tedrake</a>. I am a recipient of the <a href="https://ndseg.sysplus.com/NDSEG/Awardees/FY2019">National Defense Science and Engineering Graduate (NDSEG) fellowship</a> and the <a href="https://www.research.gov/grfp/AwardeeList.do?method=sort">NSF Graduate Research Fellowship</a>, and was named a <a href="https://sites.google.com/view/rsspioneers2022/">Robotics: Science and Systems (R:SS) Pioneer</a> in 2022.</p>

## Research focus:
<p>I design principled algorithms for <b>efficient</b>, <b>data-driven</b> robots that provide holistic, <b>full-stack</b> guarantees on <b>safety</b> and <b>reliability</b> in uncertain, <b>human-centered</b> environments. To achieve this, I leverage learned models for model-based control, and build and exploit knowledge of <i>where these models can be trusted</i> in order to enable robust behavior. Beyond machine learning and control theory, my algorithms also unify and build upon diverse tools in optimization, perception, statistics, human-robot interaction, planning, and formal methods. I also believe strongly in validating that the theoretical guarantees of my algorithms translate to the real world when deployed on hardware. These days, I am especially excited by applications in robotic manipulation and vision-based navigation. Please see <a href="projects/">this page</a> for an overview of my research directions, and <a href="publications/">this page</a> for a complete list of publications. </p>


<style>
    table.areas {
        display: table;
        text-align: center;
        margin: 0 auto;
    }
    table.areas tr {
        display: table-cell;
        width: 33%;
        border-radius: 5px;
        box-shadow: 0 0 25px 5px rgba(0,0,0,0.12);
    }
    table.areas tr:hover {
        background-color: rgba(0,117,97,0.2);
        cursor: pointer;
    }
    table.areas tr td {
        display: block;
    }
    table.areas tr td.ar_img {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 17em;
    }
    table.areas tr td.ar_img img {
        height:100%;
        object-fit: cover;
        padding-bottom: 0;
    }
    table.areas tr td.ar_text {
        display: block;
        height: 5em;
        vertical-align: top;
        padding-top: 0;
        padding-bottom: 1vh;
        line-height: 1;
    }
    @media screen and (max-width: 1024px) {
        table.areas tr {
            display: block;
            width: 100%; /* Set the width to 100% for smaller screens */
            box-sizing: border-box;
            margin-bottom: 10px; /* Adjust as needed */
        }
    }
</style>

<table class="areas">
        <tr onclick="window.location='projects/constraints'">
                <td class="ar_img"><img src="/images/auro_22_02.gif" /></td>
                <td class="ar_text"><h2 style="font-size:1.5em"><a>Safely Learning Task Specifications <br> from Humans</a></h2></td>
        </tr>
        <tr onclick="window.location='projects/trusted_domain'">
                <td class="ar_img"><img src="/images/icra_23b_alt.gif" /></td>
                <td class="ar_text"><h2 style="font-size:1.5em"><a>Reliable Planning and Control <br> with Learned Models</a></h2></td>
        </tr>
        <tr onclick="window.location='projects/output_feedback'">
                <td class="ar_img"><img src="/images/isls.gif"/></td>
                <td class="ar_text"><h2 style="font-size:1.5em"><a>Fundamental Model-Based Tools <br> for Verifiable Control</a></h2></td>
        </tr>
</table>