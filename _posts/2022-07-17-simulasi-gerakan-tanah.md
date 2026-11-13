---
layout: post
title: Ground-motion simulation with `obspy`
date: 2022-07-17 09:00:00+0700
description: Using ObsPy to simulate ground motion (displacement, velocity and acceleration)
tags: seismology, python, geophysics
categories: notebook
giscus_comments: true
related_posts: true
---


{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/02_Simulasi_Gerakan_Tanah.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/02_Simulasi_Gerakan_Tanah.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

