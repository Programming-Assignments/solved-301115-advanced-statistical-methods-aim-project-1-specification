Download Link: https://assignmentchef.com/product/solved-301115-advanced-statistical-methods-aim-project-1-specification
<br>






The Project requires us to analyse data using the knowledge obtained from this unit with assistance from a computer based statistical package.

<h1>Method</h1>

To complete this project:

<ol>

 <li>Read through this specification</li>

 <li>Complete the data analysis required by the specification</li>

 <li>Write up your analysis using your favourite word processing/typesetting program, making sure that all of the working is shown and that is it presented well.</li>

 <li>Include the student declaration text on the front page of your report. Please make sure that your <sub>name </sub>and student number are clearly displayed on the front page.</li>

 <li>Submit the report as a PDF by the due date.</li>

</ol>

<h1>Due date and Submission</h1>

The project report is due in by 11:59 p.m. on the Friday of week 12. The report must be submitted as a PDF file using the assignment submission facilities in the Project section of 301115 in vUWS.

© Copyright: Western Sydney University, 2021. No part of this publication may be reproduced or transmitted in any form or by any means, electronic or mechanical, including photocopying, recording, or by any information storage and retrieval system, without the prior written permission from the Dean, School of Computer, Data and Mathematical Sciences. Copyright for acknowledged materials reproduced herein is retained by the copyright holder. All readings in this publication are copied under licence in accordance with Part VB of the Copyright Act 1968.

<h1>Report Format</h1>

Once the required analysis is performed, write up the analysis as a report. Remember that the assessor will only see the report and will be marking the analysis based on your report. Therefore the report should contain a clear and concise description of the procedures carried out, the analysis of results, and any conclusions reached from the analysis.

The required analysis in this specification covers material presented in lectures and labs. Students should use the computer software R to carry out the required analysis and then present the results from the analysis in the report.

<h1>Marks</h1>

This project is worth 40% of your final grade, and so the project will be marked out of 40. The project consists of four parts where each part contributes equally to your final mark.

There are four parts to the project, each will be marked using the following criteria:

<ul>

 <li>Initial Investigation: Before beginning an analysis, the data should be examined to determine how the data is structured or distributed. This initial investigation helps to decide how to proceed with the analysis.</li>

</ul>

Marks          Initial Investigation Criteria Satisfied

<ul>

 <li>There is no useful initial investigation.</li>

 <li>The initial investigation provides partial insight.</li>

 <li>The initial investigation provides insight that leads to the correct analysis.</li>

 <li>The analysis of the data is required in order to answer questions.</li>

</ul>

Marks          Analysis and Results Criteria Satisfied

<ul>

 <li>The method does not lead to insightful analysis.</li>

 <li>The method is flawed, but the analysis would have provided insight had the method been correct.</li>

 <li>The correct method leads to partially correct results and analysis.</li>

 <li>The correct method leads to correct results and analysis.</li>

 <li>The correct method leads to correct results and analysis, with an insightful description of the analysis and the results.</li>

 <li>The correct method leads to correct results and analysis, with an insightful description of the analysis and the results. Limitations of the analysis are identified.</li>

 <li>A conclusion is required, explaining the results of the analysis and the answers to the question.</li>

</ul>

Marks          Conclusion Critera Satisfied

0          The conclusion does not correctly explain the results of the analysis. 1    The conclusion correctly explains the results of the analysis.

<ul>

 <li>There might be limitations to the analysis that need further exploration. Note that this section requires a higher level of thinking. It might require research or use of analytical methods taught in other units.</li>

</ul>

<table width="643">

 <tbody>

  <tr>

   <td width="74">Marks</td>

   <td width="568">Further Investigaton Critera Satisfied</td>

  </tr>

  <tr>

   <td width="74">0</td>

   <td width="568">There is no useful further investigation provided for the given analysis.</td>

  </tr>

  <tr>

   <td width="74">1</td>

   <td width="568">The further investigation provides indirect insight for the given analysis.</td>

  </tr>

  <tr>

   <td width="74">2</td>

   <td width="568">The further investigation leads to greater insight for the given analysis.</td>

  </tr>

 </tbody>

</table>

If a report is submitted late, the maximum mark it can achieve will be reduced by 10% (4 marks) per day. E.g., if a report is submitted five days late, it can receive at most 20 marks.

<h1>Declaration</h1>

<em>The following declaration must be included in a clearly visible and readable place on the first page of the report.</em>

By including this statement, we the authors of this work, verify that:

<ul>

 <li>I hold a copy of this assignment that we can produce if the original is lost or damaged.</li>

 <li>I hereby certify that no part of this assignment/product has been copied from any other student’s work or from any other source except where due acknowledgement is made in the assignment.</li>

 <li>No part of this assignment/product has been written/produced for us by another person except where such collaboration has been authorised by the subject lecturer/tutor concerned.</li>

 <li>I am aware that this work may be reproduced and submitted to plagiarism detection software programs for the purpose of detecting possible plagiarism (which may retain a copy on its database for future plagiarism checking).</li>

 <li>I hereby certify that we have read and understand what the School of Computing and Mathematics defines as minor and substantial breaches of misconduct as outlined in the learning guide for this unit.</li>

</ul>

Note: An examiner or lecturer/tutor has the right not to mark this project report if the above declaration has not been added to the cover of the report.

<h1>Project Description</h1>

The NSW Fire Rescue Services have collected data over the past few years describing fires that they have attended to. The variables recorded for each fire are:

<ul>

 <li>Location of the fire, provided as latitude and longitude.</li>

 <li>Type of land where the fire occurred.</li>

 <li>The duration of the fire in minutes.</li>

 <li>The ambient temperature in degrees Celcuis and humidity as a percentage.</li>

 <li>The date of the fire.</li>

</ul>

The data is provided in the file <sub>fire2021.csv</sub>. You have been hired as a consultant to analyse their data and help provide insight in to their four questions below.

<h2>Seasonal Effect</h2>

The fire rescue services need to know when to be prepared for fire outbreaks. Provide them with a density function plot and a density equation to estimate which times of the year that fires are likely to occur. Use the data to estimate the equation.

<h2>Allocating Equipment</h2>

The fire rescue services use fire retardants that are specific to the type of fire (either forest, grassland or desert fire retardant). The amount of retardant required is dependent on the duration of the fire. Over the past few years, the majority of fires faced have been from 300 to 400 minutes in duration and so the fire rescue services

want to know what proportions of each type of retardant to purchase.

Compute the probability of each land type conditioned on duration of the fire, plot the result, and use the plot to provide estimates of the required proportions of retardant.

<h2>Effect of Temperature on Duration</h2>

Information from the Fire Rescue Servies team shows that the duration of a fire is dependent on the temperature, but they are unsure if there are any hidden factors that have not been taken into account. Use a mixture of regressions to investigate if there are potential hidden factors that effect the duration of a fire.

<h2>Location of Fires</h2>

Finally, the Fire Rescue Services require density estimates for fire locations across NSW to help them position their stations. Plot and provide details of a model with computed coefficients that will allow them to compute the density estimate of a fire occurring, when given the location (latitude and longitude). Use the model to estimate the density at the WSU Parramatta South Campus.

Write a report containing your code and analysis of the data with each section clearly labelled. Clearly annotate your code and make sure to state any conclusions you make from each piece of analysis. The report is being marked using the marking criteria, so make sure that each piece of analysis covers all of the criteria.