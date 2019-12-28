## OpenDevoCell Development

This project will focus on improving the data science and machine learning infrastructure of the DevoWorm group. The work will focus on an extension of Summer of Code projects completed in 2017 [1] and 2019 [2]. The first two aims are to improve upon the OpenDevoCell web interface (https://open-devo-cell.herokuapp.com/) and to improve segmentation techniques overall. While the OpenDevoCell interface has been implemented as a Heroku app, we would like to develop a dashboard for interpretation as well as tighter integration with DevoZoo's (https://devoworm.github.io/devozoo.htm) collection of open-source microscopy data. The third aim is to deploy the code package as a unified Python library, which would be done in concert with improvement of segmentation techniques. 

The first priority for this Summer is to improve the web interface both in terms of interactivity and functionality. Ideally, we would like to provide users with multiple options for analysis. This includes the ability to incorporate new forms of analysis as well as algorithms for new types of data. Currently, our web app is optimized for microscopy images acquired using the SPIM technique. However, we would also like to segment microscopy images acquired using a wide range of techniques. Feeding into this is the ability to segment and obtain features for the data in our DevoZoo. The ability to extract quantitative data from these movie images is key to conducting comparative and time-series analysis. The development of a dashboard would ideally enable users to employ various machine learning and simulation techniques in one place.

These improvements are meant to increase participation in our open science initiative and make sophisticated analytical techniques more accessible to students and potential colaborators alike. We are looking for someone who can work with programming tools including HTML/CSS, TensorFlow, ReactJS, and Python. Improvements to segmentation performance might include the implementation of a pre-trained model such as Deeplab [3] or a means to plug in new components as they are developed. You will join the DevoWorm group, a project within the OpenWorm Foundation (http://openworm.org/), where we are trying to build the first virtual organism. 

Mentor: Vinay Varma (vinay.n.varma189@gmail.com) and Bradly Alicea (balicea@openworm.org), OpenWorm Foundation.

### NOTES:
[1] Siddharth Yadav, 2017:
https://github.com/sedflix/EmbryoSegmentation

[2] Vinay Varma, 2019: https://nvinayvarma189.tumblr.com/post/187265128652/semantic-image-processing-for-developmental-data

[3] see our group's work on implementing image segmentation using DeepLabv3 in TensorFlow:
https://github.com/devoworm/Digital-Bacillaria
