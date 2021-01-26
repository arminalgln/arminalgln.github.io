---
layout: splash
title: Unsupervised Event Detection, Clustering, and Use Case Exposition in Micro-PMU Measurements
Authors: "Armin Aligholian, Alireza Shahsavari, Emma Stewart, Ed Cortez, Hamed Mohsenian-Rad"
linktopaper: https://arxiv.org/abs/2007.15237
pdate: 20210125
ptype: "journal"
publisher: R1 IEEE Trans. Smart Grid
pathtoimg: /assets/images/papers/unsupervised.png
---


<h5><a href="{{page.linktopaper}}">{{page.title}}</a></h5>
<h5>Authors</h5>
<p style="font-size:20px;">{{page.authors}}</p>

<h5>Publisher</h5>
<p>{{page.publisher}}</p>

<h5>Abstract</h5>
<p style="text-align:justify">Distribution-level phasor measurement units, a.k.a, micro-PMUs, report a large volume of high resolution phasor measurements which constitute a variety of event signatures of different phenomena that occur all across power distribution feeders. In order to implement an event-based analysis that has useful applications for the utility operator, one needs to extract these events from a large volume of micro-PMU data. However, due to the infrequent, unscheduled, and unknown nature of the events, it is often a challenge to even figure out what kind of events are out there to capture and scrutinize. In this paper, we seek to address this open problem by developing an unsupervised approach, which requires minimal prior human knowledge. First, we develop an unsupervised event detection method based on the concept of Generative Adversarial Networks (GAN). It works by training deep neural networks that learn the characteristics of the normal trends in micro-PMU measurements; and accordingly detect an event when there is any abnormality. We also propose a two-step unsupervised clustering method, based on a novel linear mixed integer programming formulation. It helps us categorize events based on their origin in the first step and their similarity in the second step. The active nature of the proposed clustering method makes it capable of identifying new clusters of events on an ongoing basis. The proposed unsupervised event detection and clustering methods are applied to real-world micro-PMU data. Results show that they can outperform the prevalent methods in the literature. These methods also facilitate our further analysis to identify important clusters of events that lead to unmasking several use cases that could be of value to the utility operator.

</p>

{% if page.pathtoimg %}
<img src="{{page.pathtoimg}}" alt="{{page.title}}" />
{% endif %}