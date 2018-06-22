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
  ---      GitHub index to supplementary material from publications associated with the research project
  ---
  ---      https://github.com/johnsonwr/digitalathlete
  ---      https://guides.github.com/features/mastering-markdown/
  ---      https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
  ---
  ---      &#183; middle dot (LaTeX \cdot)
  ---
  --- 5. Modification-History
  ---      Build Author Date      Change
  ---      a35   wrj    26may2018 alpha release
  --->

<h2>http://digitalathlete.org</h2>
<br>

<table cellpadding=0 cellspacing=0>
<tr><td width=50%>
By taking a new approach and training convolutional neural networks (CNNs) with archived biomechanics data, we are creating deep learning models to facilitate accurate multidimensional on-field predictive analytics. Using test sets from multi data-captures which include ground truth force plate and/or source modelling, we see strong correspondence between measured versus predicted ground reaction forces and moments, and knee joint moments, from markers (GRF/M r>0.97, KJM r>0.88, both 8 markers, 33% stance, sidestepping). Currently, we are investigating novel methods to build models for predicting GRF/M from wearable sensors (r>0.88, 4 accelerometers, 100% stance, sidestepping).<br>
<br>
William Johnson <a href="https://github.com/johnsonwr">@johnsonwr</a><br>

bill@johnsonwr.com<br>
June 2018<br>
<a href="https://signal.org" title="Signal"><img src="_readme/Signal_Blue_Icon_32x32.format_png.resize_32x32.png" width="32" height="32"></a>
<a href="https://www.researchgate.net/profile/William_Johnson54" title="ResearchGate"><img src="_readme/rg_32x32.format_png.resize_32x32.png" width="32" height="32"></a>
<a href="https://www.linkedin.com/in/johnsonwr/" title="LinkedIn"><img src="_readme/linkedin.png" width="32" height="32"></a>
<a href="https://twitter.com/billjohnsonuwa" title="Twitter"><img src="_readme/twitter.png" width="32" height="32"></a>
<a href="https://developer.nvidia.com/academic_gpu_seeding" title="NVIDIA"><img src="_readme/NVLogo_2D_H.png" height="32" align="right"></a>
</td><td><img src="_readme/grftrain_180613080625121c25.png"></td></tr>
<tr><td colspan=2>
Caution, model files are large, you may not wish to pull the complete repository. GitHub limits file sizes to 100MB, files larger than this have been broken up using <a  href="http://manpages.ubuntu.com/manpages/trusty/man1/split.1.html" target="_blank"><b>split</b></a>. Instructions to reconstitute files are given inline.<br>
</td></tr>
</table>

<br>
<h3>Study 4: Multidimensional ground reaction forces and moments from wearable sensor accelerations via deep learning</h3>
<table>
<tr><th align="left">Keywords</th><td align="left">Biomechanics &#183; Wearable sensors &#183; Synthetic accelerations &#183; Motion capture &#183; Sports analytics</td></tr>
<tr><th align="left">WCB 2018 conference</th><td align="left">Abstract http://bit.ly/2GzYnHD</td></tr>
<tr><th align="left">Paper</th><td align="left"><i>In preparation</i></td></tr>
</table><br>

<br>
<h3>Study 3: On-field player work exposure and knee injury risk monitoring via deep learning</h3>
<table>
<tr><th align="left">Keywords</th><td align="left">Biomechanics &#183; Wearable sensors &#183; Computer vision &#183; Motion capture &#183; Sports analytics</td></tr>
<tr><th align="left">Presentation</th><td align="left">http://bit.ly/2HS7HCv</td></tr>
<tr><th align="left">Paper</th><td align="left"><i>In review (internal)</i></td></tr>
</table><br>

<br>
<h3>Study 2: Predicting athlete ground reaction forces and moments from spatio-temporal driven CNN models</h3>
<table>
<tr><th align="left">Keywords</th><td align="left">Biomechanics &#183; Supervised learning &#183; Image motion analysis &#183; Computer simulation</td></tr>
<tr><th align="left">Paper</th><td align="left"><i>In review</i></td></tr>
<tr><th align="left">Data visualization</th><td align="left"><i>In review</i></td></tr>
<tr><th align="left">MATLAB figures</th><td align="left"><i>In review</i></td></tr>
<tr><th align="left">Models</th><td align="left"><i>In review</i><br><br>

```
In review
```

</td></tr>
<tr><th align="left">Prototxt</th><td align="left"><i>In review</i></td></tr>
<tr><th align="left">CaffeNet reference</th><td align="left">https://github.com/BVLC/caffe/tree/master/models/bvlc_reference_caffenet</td></tr>
<tr><th align="left">ISBS 2017<br>conference</th><td align="left"><b>Prediction of ground reaction forces and moments via supervised learning is independent of participant sex, height and mass</b><br>
Abstract https://commons.nmu.edu/cgi/viewcontent.cgi?&article=1034&context=isbs<br>
Presentation http://bit.ly/2MvqW8c<br></td></tr>
</table><br>

<br>
<h3>Study 1: Predicting athlete ground reaction forces and moments from motion capture</h3>
<table>
<tr><th align="left">Keywords</th><td align="left">Action recognition &#183; Wearable sensors &#183; Computer simulation</td></tr>
<tr><th align="left">Paper</th><td align="left">https://link.springer.com/article/10.1007/s11517-018-1802-7</td></tr>
<tr><th align="left">Presentation (with commentary)</th><td align="left">http://bit.ly/2kcgXrw</td></tr>
<tr><th align="left">MATLAB figures</th><td align="left">https://github.com/johnsonwr/digitalathlete/tree/master/study1/figures</td></tr>
<tr><th align="left">Models</th><td align="left">https://github.com/johnsonwr/digitalathlete/tree/master/study1/models (1.9GB)<br><br>
  
```
cat grftrain_171214215406095_R_predict_model_* > grftrain_171214215406095_R_predict_model.Rda # reconstitute R model
```
  
</td></tr>
<tr><th align="left">R SPLS reference</th><td align="left">https://cran.r-project.org/web/packages/spls/index.html</td></tr>
</table><br>
