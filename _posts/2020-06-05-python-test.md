---
title:  "Python Test"
date:   2020-06-05
tags: [product management, software development, blogging]

header:
  image: "images/scenic.jpg"
  caption: "Image credit: Luke Bushman"

excerpt: "Ok... hiss"
---

Here I am explaining why I did this project, the business context and what I hope to gain... [random link](www.google.com) for more information.

Still explaining random things about the analysis and what is about to GO DOWN.


# First section Aye

Testing the first section. Blah blah explaining the post yeah yeah...

# Ok go off..

Yeahhhh heres my sick post **sick**. Here is the accuracy of my model and the data issues I encountered along the way


# Key takeaways

Includea  bunch of context about what you did and why, plus the takeaways, learnings.


```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
```


![jpg](/images/heatmap.jpg?raw=True)



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th>threshold</th>
      <th colspan="4" halign="left">precision</th>
      <th colspan="4" halign="left">recall</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>mean</th>
      <th>std</th>
      <th>min</th>
      <th>max</th>
      <th>mean</th>
      <th>std</th>
      <th>min</th>
      <th>max</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>95</th>
      <td>0.95</td>
      <td>0.957283</td>
      <td>0.060039</td>
      <td>0.857143</td>
      <td>1.0</td>
      <td>0.442526</td>
      <td>0.229691</td>
      <td>0.100000</td>
      <td>0.800000</td>
    </tr>
    <tr>
      <th>96</th>
      <td>0.96</td>
      <td>0.957283</td>
      <td>0.060039</td>
      <td>0.857143</td>
      <td>1.0</td>
      <td>0.442526</td>
      <td>0.229691</td>
      <td>0.100000</td>
      <td>0.800000</td>
    </tr>
    <tr>
      <th>97</th>
      <td>0.97</td>
      <td>0.954832</td>
      <td>0.064307</td>
      <td>0.833333</td>
      <td>1.0</td>
      <td>0.410431</td>
      <td>0.233079</td>
      <td>0.100000</td>
      <td>0.800000</td>
    </tr>
    <tr>
      <th>98</th>
      <td>0.98</td>
      <td>0.944795</td>
      <td>0.081874</td>
      <td>0.750000</td>
      <td>1.0</td>
      <td>0.345867</td>
      <td>0.206159</td>
      <td>0.076923</td>
      <td>0.727273</td>
    </tr>
    <tr>
      <th>99</th>
      <td>0.99</td>
      <td>0.930672</td>
      <td>0.106333</td>
      <td>0.666667</td>
      <td>1.0</td>
      <td>0.283582</td>
      <td>0.178153</td>
      <td>0.076923</td>
      <td>0.666667</td>
    </tr>
  </tbody>
</table>
</div>

# Attempt at using my interactive matplotlib

Pictured below.

![heatmap interactive](http://airbnb_price_heatmap.html)
