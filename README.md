# 自定义字体CSS脚本 使用选择器排除图标

用于在浏览器中自定义字体的CSS脚本，但是部分网站将一些图标设计为字体，放在一些生僻字的码位，因此导致这些网站上的图标错误显示。

本脚本收集了一些具有此类情况的网站，通过`tag:not(.class)`将其排除，目前收集了一些常见网站。

排除前：
![image](https://user-images.githubusercontent.com/14086980/165306280-bd9cb93d-8671-4862-8eb6-2b7bcb4fb768.png)
排除后：
![image](https://user-images.githubusercontent.com/14086980/165306341-978af141-d317-4aed-8b73-3e5bb9559fab.png)
