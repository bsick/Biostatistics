

# Biostatistics in Fall 2018

The course deals with simple quantitative and graphical as well as more complex methods of biostatistics. Contents: Descriptive statistics, probability theory and design of experiments, testing hypotheses, confidence intervals, correlation, simple and multiple linear regression, classification and prediction, diagnostic tests, measurement of agreement.

**Formalia:**

The slides and exercises with solutions along with literatur links are provided as learning material . However the course lives also from the interaction and discussion during the lectures and exercises as well as from explanations at the blackboard. There is no obligation to visit the lectures or exercises to attend the exam, but the exam requires sound understanding of the concepts that were taught. The course is tailored for master students of medical physics, but also master students from other programs can attend and take the exam. Subsribed PhD students can visit the lectures and also take the exam. There will be the **same exam for all students** and no extra or oral exam for PhD students. PhD students who want to earn ECTS with this course need to clarify with their PhD program head or direct advisor if this is possible by passing the standard written MC exam.

Lectures take place on Tuesdays from 10:10-11:45 in ETH HG room E21.

Exercises take place on Tuesdays from 16:15-17:00 in ETH HG room D7.1.

For doing the hands-on part on your own computer you should install R and RStudio (see first exercise).

The **exam will be a 60 minute MC quizz**. The Date will probably be **Tuesday, 11th December, in room HG E3** . It is not open book, but you are allowed to bring 2 A4 (written on both sides, all together 4 pages) of summary with you. You will not be asked for proofs or R-Code, but you need to understand the concepts and be able to interpret presented analysis results or R-outputs.

To get a feeling for the type of exam you can check out a old exam, but please be aware that the covered topics did change since then and therefore you can not expect to get questions on exactly the same topics. All topics discussed in the lectures and the exercises can be adressed in the exam inclusively all discussed aspects of linear models. Here you find a <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/test-exam-update.pdf">test-exam-updated</a> and the <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/test-exam-solutions-update.pdf">test-exam-solution-updated</a>.   
  

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
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_01_presented.pdf"> slides_01_presented</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex1-data-types.pdf"> ex_in_class_01</a> |
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex1-data-types-solution.pdf"> ex_in_class_01_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise01.pdf"> ex_01</a> | 
            <a href='https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise01_solution.pdf'> ex_01_solution</a> 
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
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_02_update.pdf"> slides_02_update</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex2-reading-plots.pdf"> ex_in_class_02</a> |
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex2-reading-plots-solution.pdf"> ex_in_class_02_solution</a>
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise02.pdf"> ex_02 </a> | 
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/survey.csv"> data_02_html</a> |
            <a href="https://www.dropbox.com/s/dyg7chzf4j550s0/survey.csv?dl=1"> data_02_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise02_solution.pdf"> ex_02_solution</a> 
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
      Inferential statistics,  model choice and model fitting
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_03_presented.pdf"> slides_03_presented</a>|
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex3-model-choice-CI.pdf"> ex_in_class_03</a> |
      <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex3-model-choice-CI-solution.pdf"> ex_in_class_03_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise03.pdf"> ex_03 </a> | 
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/pet_counts.csv"> data_03_html </a> |
            <a href="https://www.dropbox.com/s/kqvqx8d12vv20va/pet_counts.csv?dl=1"> data_03_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise03_solution.pdf"> ex_03_solution </a> 
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
      Confidence interval, t-test, p-value, relevance, significance
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_04_presented.pdf">slides_04_presented</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex4-testing-p-value.pdf"> ex_in_class_04</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex4-testing-p-value-solution.pdf"> ex_in_class_04_solution</a>
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise04.pdf"> ex_04 </a> | 
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/training.txt"> data_04_html </a> |
            <a href="https://www.dropbox.com/s/0simih4qriikc7q/training.txt?dl=1"> data_04_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise04_solution.pdf"> ex_04_solution </a>
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
      Wilcoxon test, sample size calcualtion, multiple testing
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_05_presented.pdf">slides_05_presented</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex5-p-value-distribution.pdf"> ex_in_class_05</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex5-p-value-distribution-solution.pdf"> ex_in_class_05_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise05.pdf"> ex_05 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise05_solution.pdf"> ex_05_solution </a> 
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
      Relative Risk, Odds Ratio, study types, independence test for a categorical variables: Chi-square, Fischer exact test
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_06_plan.pdf">slides_06_plan</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex6-study-types-RR.pdf"> ex_in_class_06</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex6-study-types-RR-solution.pdf"> ex_in_class_06_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise06.pdf"> ex_06 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/coffee.csv"> data_06_html </a> |
            <a href="https://www.dropbox.com/s/sud5v2iexaewh5n/coffee.csv?dl=1"> data_06_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise06_solution.pdf"> ex_06_solution </a> 
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
      Diagnostic tests, Performance measures: Sensitivity, Specificity, Positive Predictive value
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_07_plan.pdf">slides_07_plan</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex7-ROC-PPV.pdf"> ex_in_class_07</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex7-ROC-PPV-solution.pdf"> ex_in_class_07_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise07.pdf"> ex_07 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise07_solution.pdf"> ex_07_solution </a> 
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
      Simple linear regression
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_08.pdf"> slides_08 </a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex8-simple-linReg.pdf"> ex_in_class_08</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex8-simple-linReg-solution.pdf"> ex_in_class_08_solution</a> 
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise08.pdf"> ex_08 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise08_solution.pdf"> ex_08_solution </a> 
     </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUS3_ch6_linear_regression.pdf"> HSAUR3_chapter06</a> 
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
        Tests and CI in lin regression, multiple linear regression
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_09_presented.pdf">slides_09_presented</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex9-linReg.pdf"> ex_in_class_09</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex9-linReg-solution.pdf"> ex_in_class_09_solution</a>
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise09.pdf"> ex_09 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/catheter.rda"> data_09_html </a> |
            <a href="https://www.dropbox.com/s/yb46pqxdf0q16nq/catheter.rda?dl=1"> data_09_rda </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise09_solution.pdf"> ex_09_solution </a>
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
        Correlation, OLS estimates for coefficients in linear regression, model selection with warnings, Anova
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_10_presented.pdf">slides_10_presented</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex10-correlation.pdf"> ex_in_class_10</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex10-correlation-solution.pdf"> ex_in_class_10_solution</a> 
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise10.pdf"> ex_10 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/abuse.csv"> data_10_1_html </a> |
            <a href="https://www.dropbox.com/s/0idkyx2sv5zss2q/abuse.csv?dl=1"> data_10_1_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/data/mortality.csv"> data_10_2_html </a> |
            <a href="https://www.dropbox.com/s/kudy1l0kl0njs9z/mortality.csv?dl=1"> data_10_2_csv </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise10_solution.pdf"> ex_10_solution </a>
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
        Regression models for prediction, Coefficient shrinkage via Ridge Regression or Lasso, Regression to the mean
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_11_presented.pdf">slides_11_presented</a> |
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex11-prediction-models.pdf"> ex_in_class_11</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex11-prediction-models-solution.pdf"> ex_in_class_11_solution</a>  
     </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise11.pdf"> ex_11 </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/exercises/exercise11_solution.pdf"> ex_11_solution </a>
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/literature/HSAUR3_ch7_logistic_regression_glm.pdf"> HSAUR3_chapter07</a> 
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/Senn2009.3.things.to.know.pdf"> Senn2009.3.things.to.know</a> 
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
      Wrapping up regression, ANOVA
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/BS_slides_12_presented.pdf">slides_12_presented</a> | 
        <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex12-multiple-linReg.pdf"> ex_in_class_12</a> |
       <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/in_class_exercises/in-class-ex12-multiple-linReg-solution.pdf"> ex_in_class_12_solution</a> 
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/test-exam-update.pdf"> test_exam_updated </a> |
            <a href="https://github.com/bsick/Biostatistics-Fall-2018/tree/master/slides/test-exam-solutions-update.pdf"> test_exam_solution_updated </a> 
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
        Exam, 10-12am, HG E 3  
    </td>  
    <!--  Exercises  -->
    <td style="text-align: left;" valign="top">
        no exercise
    </td>  
    <!--  Lieterature  -->
    <td style="text-align: left;" valign="top">
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
