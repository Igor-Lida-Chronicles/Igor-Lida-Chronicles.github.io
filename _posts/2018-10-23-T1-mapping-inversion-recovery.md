---
layout: post
title:  "Relaxometry Series: Inversion Recovery"
author: Mathieu
categories: [ jekyll ]
image: assets/images/t1_temp.png
excerpt: Widely considered the gold standard for T1 mapping, the inversion recovery technique estimates T1 values by fitting the signal recovery curve acquired at different delays after an inversion pulse (180°). In a typical inversion recovery experiment (Figure 1), the magnetization at thermal equilibrium is inverted using a 180° RF pulse.
featured: true
hidden: false
---

<div style="text-align: justify"> 
<p>

Below is an interactive tutorial about inversion recovery T<sub>1</sub> mapping that is powered by <a href="https://github.com/neuropoly/qMRLab" target="_blank">qMRLab</a>. Most figures are generated with <a href="https://plot.ly/python/" target="_blank">Plot.ly</a> – you can play with them by hovering your mouse over the data, zooming in (click and drag) and out (double click), moving the sliders, and changing the drop-down options. To view the code that was used to generate the figures in this blog post, hover your cursor in the top left corner of the frame that contains the tutorial and click the checkbox "All cells" in the popup that appears.

</p>

<p>

A Jupyter Notebook version of this blog post is also available through MyBinder, and can be viewed <a href="https://mybinder.org/v2/gh/qMRLab/t1_notebooks/master?filepath=ir_blog%2FInversionRecovery.ipynb" target="_blank">here</a>. There you can modify the code, change the figures, and regenerate the html that was used to create the tutorial below. It is powered by <a href="https://vatlab.github.io/sos-docs/" target="_blank">Script of Scripts (SoS)</a>, allowing us to process the data using qMRLab in MATLAB/Octave and plot the figures with Plot.ly using Python, all within the same Jupyter Notebook.

</p>

<p>

<b> For best user experience with interactive tutorials, we recommend using a laptop or a desktop computer.</b>

</p>


</div> 

<iframe src="https://s3.ca-central-1.amazonaws.com/qmrlab-blogs/InversionRecovery.html" width="100%" height="9600px" style="border:none;"></iframe>
