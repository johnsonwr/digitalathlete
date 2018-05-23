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
The digitalathlete repository contains supplementary material from the publications associated with this research project<br>
<br>
Large files have been split into 100MB pieces to meet GitHub requirements<br>
http://manpages.ubuntu.com/manpages/trusty/man1/split.1.html<br>
Caution, https://github.com/johnsonwr/digitalathlete/tree/master/study1/models folder is large (>2GB)<br>
<br>
<h3>Study 1: Predicting athlete ground reaction forces and moments from motion capture</h3>

| --- | --- |
| Paper | https://link.springer.com/article/10.1007/s11517-018-1802-7 |
| Models | https://github.com/johnsonwr/digitalathlete/tree/master/study1/models |
| MATLAB figures | https://github.com/johnsonwr/digitalathlete/tree/master/study1/figures |
| Video presentation | http://bit.ly/2kcgXrw |

The R model has been split, to reintegate use cat<br>
Model format reference https://cran.r-project.org/web/packages/spls/index.html<br>

```
cat grftrain_171214215406095_R_predict_model_* > grftrain_171214215406095_R_predict_model.Rda
```

<br>
William Johnson<br>
bill@johnsonwr.com<br>
May 2018<br>
