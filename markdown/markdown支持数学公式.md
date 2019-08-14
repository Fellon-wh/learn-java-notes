[TOC]

<!DOCTYPE html>
<!-- mathjax config similar to math.stackexchange -->
<script type="text/x-mathjax-config">
MathJax.Hub.Config({

    jax: ["input/TeX", "output/HTML-CSS"],
    tex2jax: {
        inlineMath: [ ['$', '$'] ],
        displayMath: [ ['$$', '$$']],
        processEscapes: true,
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
    },
    messageStyle: "none",
    "HTML-CSS": { preferredFont: "TeX", availableFonts: ["STIX","TeX"] }
});
</script>
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"> </script>

# Markdown中添加对数学公式的支持

### 一、下载MathJax  
地址：[https://www.mathjax.org/](https://www.mathjax.org/)  

![](../images/markdown/mathjax.png)    

将MathJax-master.zip解压到项目里边，如下我这里解压到learn/tools/js目录下    

![](../images/markdown/mathjax2.png)    

### 二、Markdown中使用

在markdown的最开始引入如下script头,如下：

![](../images/markdown/mathjax3.png)      

浏览器中显示如下
![](../images/markdown/mathjax4.png)      


 $$\frac{1}{2}$$

 $$a^2$$

$$J(\theta) = \frac 1 2 \sum_{i=1}^m (h_\theta(x^{(i)})-y^{(i)})^2$$

$$sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}$$

$\ce{C6H5-CHO}$
$\ce{$A$ ->[\ce{+H2O}] $B$}$
$\ce{SO4^2- + Ba^2+ -> BaSO4 v}​$

$\left(\frac{\sqrt x}{y^3}\right)$

$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$ 

### 三、支持数学表达式的Markdown编辑器

- [Typora](https://typora.io/) 这个是国人开发的Markdown阅读编辑器，有Mac、Windows、Linux版本体验效果非常好



推荐：

- https://www.jianshu.com/p/a0aa94ef8ab2 MathJax教程