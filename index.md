[comment]: # (ATTENTION: This is a template. You can adapt and expand it as you like and serves as a solid starting point.)
[comment]: # (Be aware that most of the code is provided via 'html' and 'css' format.)
[comment]: # (To make comments like this, you can simply copy one of these lines and change everything between the parentheses.)
[comment]: # (Before starting, first read carefully all comments and try to get familiar with the template.)

[comment]: # (Tool recommendation: Visual Studio Code - https://code.visualstudio.com/)
[comment]: # (This is just a personal recommendation because VS Code is free, easy to use and offers a lot of useful extensions.)
[comment]: # (VS Code offers a extention which allows you to preview your document within the Code Editor - which is very useful.)
[comment]: # (Extension recommendation: Markdown All in One --> helpfull commands and options)
[comment]: # (Extension recommendation: Markdown Preview Enhanced --> allows to preview page within VS Code)
[comment]: # (Extension recommendation: Markdown PDF --> allows to export Markdown to pdf, html, png, jpeg)

[comment]: # (To convert the markdown file to html with 'Markdown PDF' [1] open in VS Code the preview, [2] right click into the window with the preview, [3] Click on HTML --> HTML cdn hosted. --> Do NOT right click and export where your code is, since it will be without the format)

[comment]: # (When you are done, upload your work and use GitHub Pages to create your own website.)
[comment]: # (In the folder 'github_pages_tutorial' you can find pictures for the instructions. Be sure that the exported .html file is name 'index.html')
[comment]: # (Additionally the link to the official instruction: https://pages.github.com/)

[comment]: # (In this section you can define rules for special blocks or formats.)
<style>
.generalRules {
  display: flex;
  font-family: "Times New Roman", Times, serif;
  flex-direction:column;
  max-width: 960px
}
h1 {
  font-style: italic;
}
.titleTextContent {
  border: 4px solid; 
}
img {
  max-width: 100%
}markdown-pdf: Export (html)
.titleImage {
  flex-basis: 40%;
}
.titleText {
  text-align: justify;
  font-size: 18px;
  padding: 15px;
  font-weight: bold;
}
.sectionHeader {
  padding-top: 20px;
  text-align: left;
  font-size: 35px;
  font-weight: 500;
  color: #B0D2D3;
  line-height: 45px;
}
.horizontalLine {
  width: 100%;
  border-top:4px solid #B0D2D3; 
  padding-bottom: 10px;
}
.sectionTextBox {
  border: 1px solid; 
}
.sectionText {
  text-align: justify;
  font-size: 18px;
  padding-top: 10px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 10px;
  font-weight: normal;
}
.spaceBetween {
  padding: 10px;
}
.downloadContainer {
  background-color: #B0D2D3;
  height: 150px;
  width: 100%;
  color: white;
  font-size: 40px;
  text-align: center;
}
.downloadbutton {
  background-color: #B0D2D3;
  border: 5px solid white;
  border-left: 50px solid white;
  border-right: 50px solid white;
  color: white;
  height: 50px;
  width: 100%;
  cursor: pointer;
  font-size: 20px;
  border-radius: 25px;
}
.downloadbutton:hover {
  background-color: #B0D2D3;
}
</style>

[comment]: # (Here starts the section where you are intented to insert your work.)
<body>
<div class="generalRules">

[comment]: # (Title)
<div style="text-align: center;">
  <h1>Does gamification affect learning outcomes?</h1>
</div>

[comment]: # (Image below title if needed.)
<div style="display: flex; justify-content: center;">
  <div class="titleImage">
    <img src="images/gamification.jpg" width="400" height="300">
  </div>
</div>

<div class="Text" style="font-size: 8px; text-align: center;">
https://commons.wikimedia.org/wiki/File:Gamification-in-business-illustration-web.jpg
</div>


[comment]: # (Text below the title)
<div class="sectionTextBox">
<div class="titleText">
Does the implementation of gamification into the educational practice has a measurable impact on cognitive, motivational, and behavioral learning outcomes? What contextual, situational, and additional factors contribute to a successful application of gamification. Although a considerable amount of research has been done in the field of gamification the results of the effects seem to be ambiguous. With the goal to clarify this issue and to answer the initial question Sailer and Homner conducted a meta-analysis titled “The Gamification of Learning: a Meta-analysis”. This short review describes the theoretical and conceptual background of gamification in learning environments and reports the empirical evidence of the meta-analyses.
</div>
</div>

[comment]: # (Header of a section with a horizontal line)
<div class="sectionHeader">
  METAANALYSIS OVERVIEW
  <div class="horizontalLine"> </div>
</div>

<div class="sectionTextBox" style="display: flex;">
  <div style="flex: 1;">
    <div class="sectionText">
      <b>Focus of the study:</b> Effects of gamification in cognitive, motivational, and behavioral learning outcomes.
    </div>
    <div class="sectionText">
      <b>Target group:</b> People in a learning environment.
    </div>
        <div class="sectionText">
      <b>Average effect size:</b> Significant positive effect on cognitive (g=0.49), motivational (g=0.36), and behavioral (g=0.25) learning outcomes.
    </div>
  </div>
  <div style="flex: 1;">
    <div class="sectionText">
      <b>Additional results:</b>
      <ul>
        <li>Inclusion of game fiction and social interaction significantly moderate the effect of gamification on behavioral learning outcomes.</li>
        <li>No publication bias was found.</li>
      </ul>
    </div>
  </div>
</div>



[comment]: # (Little hack to insert space between the current and next element)
<div class="spaceBetween"></div>

[comment]: # (Box and Button to download the pdf. change example.pdf to the real name when you are finished. e.g. short-review-lastname-firstname.pdf)
<div class="downloadContainer">
<b>Download short review</b> 
<a href="gamification_learning_outcomes.pdf">
<button class="downloadbutton"> <b>Download PDF</b></button>
</a>
</div>

[comment]: # (Little hack to insert space between the current and next element)
<div class="spaceBetween"></div>

[comment]: # (Header of a section with a horizontal line)
<div class="sectionHeader">
  READ SHORT REVIEW ONLINE
  <div class="horizontalLine"> </div>
</div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>Introduction</b>
</div>
<div class="sectionText">
<b>Gamification</b> is defined as the use of game design elements, mechanics, and dynamics in a non-game context (Deterding et al., 2011). In an educational setting gamification aims to enhance motivation and engagement during learning activities based on the inherent motivational aspects of games. In contrast to game-based learning approaches that imply full developed (serious) games, gamification focuses on making existing learning process more game like. The conceptual framework for the relationship between gamification and learning can be provided by the following two theories: the theory of gamified learning and the self-determination theory.
</div>
<div class="sectionText">
The <b>theory of gamified learning</b> proposes that gamification can - by directly influencing behaviors and attitudes related to learning – positively affect the relationship between instructional content and learning outcomes. The overall improved learning expirience should lead to improved learning outcomes.
</div>
<div class="sectionText">
The <b>self-determination theory</b> is a well establish framework in the gaming context. It proposes that the satisfaction of the psychological needs for autonomy, competence, and social relatedness are crucial for intrinsic motivation and therefore for the learning success. The theory further highlights the importance of the learning environment and the provision of feedback, both of which can be provided through the implementation of gamification.
</div>
<div class="sectionText">
Despite this theoretical background many studies in the context of gamification lack a theoretical foundation and a methodological rigor in the implementation. This may be the reason that up to the date of the conduction of this meta-analysis mixed findings have been reported. The few previously undertaken meta-analyses suggest a tendency for gamification to have a positive impact on learning outcomes but with many aspects being inconclusive. To address these shortcomings the authors were motivated to undertake their own meta-analysis.
</div>
</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>What is this study about?</b>
</div>
<div class="sectionText">
The objective of the following meta-analysis was to explore and statistically synthesize current research findings concerning the impact of gamification on cognitive, motivational, and behavioral learning outcomes compared to conventional instructional methods. Cognitive learning outcomes include conceptual knowledge (facts, principles, and concepts) and application-oriented (procedural, strategic, and situational) knowledge. Motivational learning outcomes are characterized by motivation, attitudes, engagement, and feelings of self-efficacy. Behavioral outcomes refer to motor skills and task-specific performance.
</div>

<div class="sectionText">
The initial search involved querying various academic databases, Google Scholar, and reference lists from prior meta-analyses for the term "gamification" and "gamif*". The authors did not include any specific game design elements in the search terms to avoid bias. The resulting 786 full-text articles were screened for eligibility according to the following criteria:
<ul>
  <li>Gamification as one condition in an intervention study</li>
  <li>At least one learning outcome must be assessed</li>
  <li>Article needs to be written in English</li>
  <li>Quantitative statistical methods need to be applied, and the data needs to be available</li>
  <li>Comparison to a non-gamification control group is needed</li>
</ul>
</div>

<div class="sectionText">
The years of publication were not restricted but had to be before the date of the search (March 2017). After the exclusion process, 38 eligible articles were left. Three of these articles reported a very high effect size and were excluded as outliers as well. The final sample of studies for cognitive learning outcomes included 19 primary studies and 1686 participants. The sample for motivational and behavioral outcomes consisted of 16 primary studies (2246 participants) and 9 primary studies (951 participants), respectively.
</div>

<div class="sectionText">
In order to not only answer the question if gamification has a positive effect on learning outcomes but also how, Sailer and Homner additionally conducted a series of moderator analyses. The different moderating factors should represent the conceptual heterogeneity in gamification, for example, different game design elements. Based on an iterative process, the following contextual, situational, and methodological moderators were included:
<ul>
  <li>Inclusion of game fiction (game world and story elements)</li>
  <li>Social interaction (collaboration and competition)</li>
  <li>Learning arrangement of comparison group (passive, active, untreated)</li>
  <li>Period of time (short-, middle-, longtime)</li>
  <li>Research context (school, higher education, work-related)</li>
  <li>Randomization (experimental, quasi-experimental)</li>
  <li>Design (post-test only, pre- and post-tests)</li>
  <li>Instruments (standardized, adapted, self-developed)</li>
</ul>
</div>

</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>What does this study find?</b>
</div>
<div class="sectionText">
The results of the meta-analysis indicate a favourable impact of gamification on all three learning outcomes. A high heterogeneity of study results (implying varying effects of gamification across different studies) was reported. Publication bias was explored using funnel plots, selection models and the fail-safe-numbers, which all indicate the absence of publication bias. In more details the results show:
<ul>
  <li>a significant small effect of gamification on cognitive learning outcomes (g = .49, SE = .10, p < .01, 95%CI [0.30, 0.69, a significant amount of heterogeneity (Q(18) = 57.97, p < .01, I2 = 72.21%) and robustness against publication bias  (fail-safe N = 469)</li>
  <li>a significant small effect of gamification on motivational learning outcomes (g = .36, SE = .09, p < .01, 95% CI [0.18, 0.54]), a significant amount of heterogeneity (Q(15) = 73.54, p < .01, I2 = 75.13%) and robustness against publication bias  (fail-safe N = 316)</li>
  <li>a significant small effect of gamification on behavioral learning outcomes (g = .25, SE = .11, p < .05, 95% CI [0.04, 0.46]), a significant amount of heterogeneity (Q(9) = 22.10, p < .01, I2 = 63.80%) and robustness against publication bias  (fail-safe N = 136)</li>
</ul>
</div>
<div class="sectionText">
The substantially high heterogeneity in the study results can partly be explained by the analysis of the moderating factors. Not all possible levels of moderators could be compared due to the limited number of available studies for every condition. The moderator analysis yielded the following results:
<ul>
  <li>The Inclusion of game fiction had no influence on the effects of gamification on cognitive and behavioral learning outcomes but the positive effect of gamification on motivational learning outcomes was only existent in the inclusion of game fiction condition (Q(1) = 5.45, p < .05, no sig. residual variance left (p = .08)).</li>
  <li>The different forms of social interaction also only showed significant results for the behavioral outcomes: competitive-collaborative interaction outperformed no social interaction (Q(2) = 12.80, p < .01)</li>
  <li>The time period only had a significant influence on the motivational learning outcomes: gamification interventions that lasted between days and half a year had a greater effect than interventions that lasted a day or less.</li>
  <li>The research context was only relevant for cognitive outcomes: The effect of gamification was significant larger in school settings than in higher education and work settings Q(2) = 12.48, p < .01).</li>
  <li>The randomization aspect only showed a difference for motivational learning outcomes: the significant effect of gamification on motivational learning outcomes was only given for quasi-experimental studies but not for experimental studies (Q(1) = 4.67, p < .05).</li>
  <li>he moderators learning arrangement of the comparison group, design and instrument either showed no significant result or could not be deducted due to limited number of studies.</li>
</ul>
</div>
</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>How does the Digital Psychology Lab teaching evaluate this study?</b>
</div>
<div class="sectionText">
The quality and validity of the meta-analysis is evaluated based on the following five questions of the Abelson criteria (1995).
</div>
<div class="sectionText">
<b>How substantial is the outcome?</b><p>
The consistent overall effect size indicates a small to medium effect of gamification for cognitive learning outcomes (g = .49) and a small effect for motivational and behavioral learning outcomes (g = .36 and .25). This means that around 69% of people with a gamified learning intervention have better cognitive learning outcomes than the average of the control groups, who had a conventional learning intervention. For motivational and behavioral learning outcomes the percentages are around 64% and 60% respectively. The strict exclusion criteria and the exact implementation procedure further contribute to the quality of the meta-analysis. For cognitive learning outcomes an even stricter methodological rigor concerning the design (only including studies with pre- and post-test) shows a similar significant small effect size of g = 0.42. Overall, the findings of this meta-analyisis can be considered substantial.
</div>
<div class="sectionText">
<b>How precise are the outcomes?</b><p>
The effects of gamification are assessed for cognitive, motivational and behavioral outcomes individually. Specific game design elements were not part of the search strategy, but some game elements were included in the moderator analysis. In addition, situational, contextual, and methodological moderators were also included. Inclusion of game fiction and a competitive-collaborative setting increased the behavioral learning outcome. The impact of gamification in school settings is larger than in higher education and work settings. This suggest that overall the outcomes can be considered precise.
</div>
<div class="sectionText">
<b>Is the outcome generalizable?</b><p>
Although some moderator analysis showed specific effects, the meta-analysis demonstrates that the overall effect is stable and shows that gamification in general can contribute in many different ways and settings to improved learning outcomes. Despite strict selection criteria a decent number (38) of primary studies were included in the meta-analysis, that captured a broad spectrum of applications of gamification. Most moderator test are based on a limited number of studies and therefore these results should be considered preliminary with limited reliability. Future research is needed to further examine the influence of (additional) moderator variables and to produce more reliable results. The authors themselves suggest including participant characteristics (familiarity with gaming, personality traits) and different types of feedback in future studies. Moreover, the authors also admit that many aspects of game design were not included in the moderator analysis, although prior research suggests, that they may have an impact on the positive implementation of gamification. (e.g. the implementation of achievements had a better effect if the achievements were difficult and rare, Groening and, Binnewies 2019). Another aspect which is not considered in the current meta-analysis are differences in culture and language. But in summary the generalizability of the overall effect can be considered as high.
</div>
<div class="sectionText">
<b>How relevant is the outcome?</b><p>
The meta-analysis from Sailer and Homner can be considered as scientific relevant because it delivers a valuable and more reliable estimation of the effect of gamification on learning outcomes. The more rigorously conducted meta-analysis – it includes more primary studies, has a stricter focus on the quality of the studies and has a more differentiated analytical approach - is able to clarify the partly ambiguous results of prior studies and meta-analyses. The conducted moderator analyses provide more specific and detailed insights in the moderating factors of the positive effects of gamification on the learning outcome. Furthermore, the authors give a framework for future research and describe additional factors that may influence the implementation and the positive effects of gamification – these potentially moderating factors should be considered in future research designs.
</div>
<div class="sectionText">
<b>How high is the credibility of the outcome?</b><p>
The meta-analysis is in line with the considerations of official guidelines, such as the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) guidelines or the APA Meta-Analytic Reporting Standards (MARS). Sailer and Homner clearly described their search strategy, which databases they used, stated their inclusion and exclusion strategy, showed the selection process in a PRISMA flow diagram, explained their coding procedure including a interrater reliability (ranging from κ = .76 to perfect agreement). The publication bias is assessed through funnel plots, selection models and fail-safe numbers. They clearly described the levels of the moderating factors and generally followed the guidelines for the applied statistical methods, the displayed results and the recommended discussion points (considerations, implications and limitations). Solely a comprehensive overview, including the coding of the moderators, over the included primary studies is missing. In summary, the quality of the meta-analysis can be considered as high.
</div>
</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>Conclusion for teaching practice</b>
</div>
<div class="sectionText">
The incorporation of gamification in the teaching practice positively impacts the learning outcomes on several dimensions: The implementation of gamification elements such as rewards, story elements, interactive cooperative activities, or leaderboards during learning activities enhances cognitive learning outcomes such as the acquisition of conceptual knowledge and application-oriented knowledge. It also contributes to increased motivation, engagement, and active participation among learners. Finally, it has been shown, that gamification positively influences behavioral learning outcomes such as problem solving and collaborative abilities and perseverance. Although to a lesser degree, these findings are not only valid for a school setting but also for higher education and a work context and therefore highlight the potential for the implementation of gamification in a wide variety of educational settings.
</div>
<div class="sectionText">
Gamification is not a substitute for conventional teaching techniques nor for the important personal relationships between educators and learner, but a valuable complement that enhances learning experience of the learners. On the flip side the utilization of gamification can have positive effects for the educators too ( such as enhanced classroom dynamics, immediate feedback and more data-driven insights).
</div>
<div class="sectionText">
Finally, it is important to further explore contributing factors to the positive effects of gamification such as long-term effects on learning outcomes or the influence of individual personality characteristics on the effects of gamification to be able to provide an even better and more personalized learning expirience. 
</div>
</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>Study example</b>
</div>
<div class="sectionText">
Sailer, Hence, Mayr and Mandl (2017) conducted a study to examine the impact of specific game design elements on motivation. They noted that previous research on gamification has been lacking theoretical foundation and study design quality, with studies being indiscriminate regarding different aspects of gamification. Consequentially the authors sought to explore, based on a self-determination framework, whether the need for competence, the need for autonomy and the need for social relatedness are addressed by different game design elements.
</div>
<div class="sectionText">
In their randomized controlled study, conducted in an online simulation environment, 419 out of 699 participants completed the game and the subsequent questionnaire. An additional 88 persons had to be excluded since they were unable to perceive the specific game elements. The findings align with the expectations, indicating that game design elements badges, leaderboards and performance graphs positively effected the satisfaction of the competence need. Furthermore, the need for social relatedness was positively affected by the game design elements avatars, meaningful stories, and teammates. The need for autonomy was conceptual divided into perceived task meaningfulness and perceived decision freedom. Both aspects were not affected by specific game elements as expected: badges, leaderboards and performance graphs contributed to an increase in perceived task meaningfulness. The Perceived decision freedom was not affected by any game design element. The authors concluded that the self-determination theory provides a suitable framework for investigating the effects of gamification on motivation and that different game design elements can affect different aspects of motivation, underscoring the complexity of motivational factors in gamified environments.

</div>
</div>

[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>References</b>
</div>
<div class="sectionText">

Deterding, S., Dixon, D., Khaled, R., & Nacke, L. (2011). From game design elements to gamefulness: defining “gamification”. In A. Lugmayr (Ed.), Proceedings of the 15th International Academic Mindtrek Conference: Envisioning Future Media Environments (pp. 9–15). New York: ACM. [https://doi.org/10.1145/2181037.2181040](https://doi.org/10.1145/2181037.2181040)
<p>

Groening, C., & Binnewies, C. (2019). “Achievement unlocked!” - The impact of digital achievements as a gamification element on motivation and performance. Computers in Human Behavior, 97, 151–166. [https://doi.org/10.1016/j.chb.2019.02.026](https://doi.org/10.1016/j.chb.2019.02.026)
<p>

Sailer, M., Hense, J. U., Mayr, S. K., & Mandl, H. (2017). How gamification motivates: an experimental study of the effects of specific game design elements on psychological need satisfaction. Computers in Human Behavior, 69, 371–380. 
[https://doi.org/10.1016/j.chb.2016.12.033](https://doi.org/10.1016/j.chb.2016.12.033)
<p>

Sailer, M., & Homner, L. (2020). The Gamification of Learning: a Meta-analysis. Educational Psychology Review, 32(1), 77–112. [(https://doi.org/10.1007/s10648-019-09498](https://doi.org/10.1007/s10648-019-09498)

</div>

</div>


[comment]: # (Hack for space and horizontal line)
<div class="spaceBetween"></div>
<div class="horizontalLine"> </div>

[comment]: # (Text Box of a section)
<div class="sectionTextBox">
<div class="sectionText">
<b>Disclaimer: Use of Large Language Model</b>
</div>
<div class="sectionText">

This short review at hand incorporates the utilization of a Large Language Model (ChatGPT), to aid in  ideation, sentence formulation and code generation.
</div>
</div>
</body> 
