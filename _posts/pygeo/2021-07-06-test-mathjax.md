---
title: Mengetes MathJax
description: "Mengetes MathJax untuk menulis persamaan matematika di web"
syntax: true
category: note
tags: jekyll 
permalink: /blog/mathjax-test
---

Sebagai mahasiswa yang seringkali berkutat dengan rumus-rumus matematika memaksa saya memastikan web ini juga dapat disusupi persamaan-persamaan jahat tersebut. Dalam kasus ini maka MathJax dapat menjadi penyelamat. MathJax dapat dengan mudah dimasukkan ke Jekyll atau _site generator_ lain dengan memasukkan _script_ di bawah ini ke dalam template:

```javascript
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        processEscapes: true
      }
    });
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
```

Disini saya mengetes dengan mencoba memasukkan persamaan matematika sederhana di _markdown_ dengan kode:

```mathjax
$$ e^{i\theta} = \cos(\theta) + i\sin(\theta) $$
```

Maka akan muncul Persamaan Euler:

$$ e^{i\theta} = \cos(\theta) + i\sin(\theta) $$

😄😄😄