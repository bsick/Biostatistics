

# Biostatistics in Fall 2018

The course deals with simple quantitative and graphical as well as more complex methods of biostatistics. Contents: Descriptive statistics, probability theory and design of experiments, testing hypotheses, confidence intervals, correlation, simple and multiple linear regression, classification and prediction, diagnostic tests, measurement of agreement.

**Formalia:**

The slides and exercises with solutions along with literatur links are provided as learning material . However the course lives also from the interaction and discussion during the lectures and exercises as well as from explanations at the blackboard. There is no obligation to visit the lectures or exercises to attend the exam, but the exam requires sound understanding of the concepts that were teached. The topics of missed lectures must be learned in self-study. The course is tailored for master students of medical physics, but also master students from other programs can attend and take the exam. Subsribed PhD students can visit the lectures and also take the exam. There will be the **same exam for all students** and no extra or oral exam for PhD students. PhD students who want to earn ECTS with this course need to clarify with their PhD program head or direct advisor if this is possible by passing the standard written MC exam.

Lectures take place on Tuesdays from 10:10-11:45 in ETH HG room E21.

Exercises take place on Tuesdays from 16:15-17:00 in ETH HG room D7.1.

For doing the hands-on part on your own computer you should install R and RStudio (see first exercise).

The exam will be a 45 minute MC quizz. The Date will probably be Tuesday, 11th December (will be fixed soon) and the room will be announced asap.

The currently planned topics are summarized in the <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/formalia_public/semesterplan15092018.pdf"> semester plan</a>.
  

## Material for Lectures and Exercises  
<!--  
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Note on table no empty lines / Bitte keine Leerzeilen 
Otherwise the rendering is broken
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
-->
<table  class="zebra" width="width:100%">
  <tr>
      <th style="text-align: left;" width="%5">Week</th>
      <th style="text-align: left;" width="%5">Date</th>
      <th style="text-align: left;" width="%65">Topics and Lectures notes</th>
      <th style="text-align: left;" width="%20">Exercises</th>
      <th style="text-align: left;" width="%15">Literature</th>
  </tr>
    <!--  ------------------------------------- -->
    <!--  week 1 -->
    <!--  ------------------------------------- -->
    <!-- week  -->
    <td style="text-align: left;" valign="top">
      01
     </td>  
         <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 18.9.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
      introduction / basic terms / datatypes / uni-variate graphical displays
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_01_presented.pdf"> slides_01_presented</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/Exercise0.pdf"> ex_0</a> | 
            <a href='https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/Exercise0_solution.pdf'> ex_0_solution</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch1_introduction_to_R.pdf"> HSAUR3_chapter01</a> 
        </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 2 -->
    <!--  ------------------------------------- -->
      <tr>
            <!-- week  -->
    <td style="text-align: left;" valign="top">
      02
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 18.9.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
     key numbers for location / uni- and bi-variate graphical displays
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_02_presented.pdf"> slides_02_presented</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/Exercise1.pdf"> ex_1</a> | 
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/survey.csv"> data_1_csv</a> |
            <a href="https://www.dropbox.com/s/dyg7chzf4j550s0/survey.csv?dl=1"> data_1_html </a>
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/Exercise1_solution.pdf"> ex_1_solution</a> |
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch2_graphical_display.pdf"> HSAUR3_chapter02</a>  
      </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 3 -->
    <!--  ------------------------------------- -->
     <tr>
      <!-- week  -->
    <td style="text-align: left;" valign="top">
      03
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 02.10.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
      Inferential statistics,  model choice and model fitting, Confidence interval, significance, relevance
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_03_plan.pdf"> slides_03_plan</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/Exercise1.pdf"> ex_2</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/IPSUR-vignette-distributions-week3.pdf"> IPSUR-distributions</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 4 -->
    <!--  ------------------------------------- -->
             <tr>
      <!-- week  -->
    <td style="text-align: left;" valign="top">
      04
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 09.10.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch4_simple_inference.pdf"> HSAUR3_chapter04</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 5 -->
    <!--  ------------------------------------- -->
                   <tr>
      <!-- week  -->
    <td style="text-align: left;" valign="top">
      05
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 16.10.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            see last week 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 6 -->
    <!--  ------------------------------------- -->
                           <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      06
     </td>  
     <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 23.10.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch4_simple_inference.pdf"> HSAUR3_chapter04</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 7 -->
    <!--  ------------------------------------- -->
                                <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      07
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 30.10.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/statistics.notes.diagnostic.tests.pdf"> statistics.notes.diagnostic.tests</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 8 -->
    <!--  ------------------------------------- -->
                                       <tr>
      <!-- week  -->
    <td style="text-align: left;" valign="top">
      08
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 06.11.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch6_linear_regression.pdf"> HSAUR3_chapter06</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 9 -->
    <!--  ------------------------------------- -->
                                               <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      09
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 13.11.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
    see last week
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 10 -->
    <!--  ------------------------------------- -->
                                                     <tr>
      <!-- week  -->
    <td style="text-align: left;" valign="top">
      10
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 20.11.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
        see last week
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 11 -->
    <!--  ------------------------------------- -->
                                                          <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      11
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 27.11.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch7_logistic_regression_glm.pdf"> HSAUR3_chapter07</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 12 -->
    <!--  ------------------------------------- -->
                                                                  <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      12
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 04.12.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch9_tree_modes.pdf"> HSAUR3_chapter09</a> 
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 13 -->
    <!--  ------------------------------------- -->
      <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      13
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 11.12.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            see last week
     </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
    <!--  ------------------------------------- -->
    <!--  Woche 14 -->
    <!--  ------------------------------------- -->
     <tr>
     <!-- week  -->
    <td style="text-align: left;" valign="top">
      14
     </td>  
    <!-- Date -->
    <td style="text-align: left;" valign="top">
      Tuesday 18.12.2018
     </td>  
     <!-- Lectures -->
  	<td style="text-align: left;" valign="top"> 
        <a href=""> XX</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href=""> XX</a> | 
            <a href=""> XX</a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch11_survival_analysis.pdf"> HSAUR3_chapter11</a> 
    </td>  
        <!-- 
      </ul>
    </td>   
  </tr>
