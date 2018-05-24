<!---
  ---
  --- 1. Filename, Creation-Date
  ---      digitalathlete/README.md, 22may2018
  ---
  --- 2. Original-Author, Email-Address
  ---      Copyright (c) MMXVIII
  ---      William JOHNSON, bill@johnsonwr.com
  ---
  --- 3. Last-Updated-By, Email-Address
  ---      William JOHNSON, bill@johnsonwr.com
  ---
  --- 4. Notes
  ---      https://guides.github.com/features/mastering-markdown/
  ---      https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
  ---
  --- 5. Modification-History
  ---      Build Author Date      Change
  ---      n/a   wrj    22may2018 alpha release 
  --->

<h2>Project overview http://digitalathlete.org</h2>
<br>
This digitalathlete repository contains supplementary material from publications associated with the research project<br>
<br>
William Johnson @johnsonwr<br>

bill@johnsonwr.com<br>
May 2018<br>
<br>

<h3>Study 2: Predicting athlete ground reaction forces and moments from spatio-temporal driven
CNN models</h3>
<i>In review</i><br>
<br>

<h3>Study 1: Predicting athlete ground reaction forces and moments from motion capture</h3>
<table>
<tr><th align="left">Paper</th><td align="left">https://link.springer.com/article/10.1007/s11517-018-1802-7</td></tr>
<tr><th align="left">Video presentation</th><td align="left">http://bit.ly/2kcgXrw</td></tr>
<tr><th align="left">Models</th><td align="left">https://github.com/johnsonwr/digitalathlete/tree/master/study1/models (2GB)</td></tr>
<tr><th align="left">MATLAB figures</th><td align="left">https://github.com/johnsonwr/digitalathlete/tree/master/study1/figures</td></tr>
</table>
R model format reference https://cran.r-project.org/web/packages/spls/index.html<br>
GitHub file size limits require the R model to be <b>split</b>, to reintegate use <b>cat</b><br>

```
cat grftrain_171214215406095_R_predict_model_* > grftrain_171214215406095_R_predict_model.Rda
```
