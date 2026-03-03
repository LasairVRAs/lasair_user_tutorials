<p align="center">
<img src="tutorials/img/lvra.png" alt="lvra" width="50"/>
</p>

<h1 align="center">  Lasair User Tutorials </h1>


This repository is based on the [Lasair examples](https://github.com/lsst-uk/lasair-examples) but reframed and expanded to provide a more detailed understanding of what the code in the example does. 

Everything I struggled with as a dirst time user, I put in these tutorials in the hopes it will help others. 




## How to use these examples?

There are three kinds of resources:
* **Tutorials** which are detailed jupyter notebooks detailing our **API recipes**, our **kafka streams** and **how to handle the data** (e.g. make lightcurves, plot cut-outs)

* **Understans the features**: These notebooks are step-by-step explainers on how some key Lasair features (e.g. Extinction Corrected magnitudes, Black Body Temperatures from nightly pairs) are calculated. You can run these noteooks and play with them, but it is typically not code you will then copy into you utilities. I have not gone over all of the Lasair features; I started with the ones I was keen to understand better and had time to dive into. You are welcome to add to this or make requests. I will slowly build this as my use of Lasair expands

* **Template Scripts**: Full python scripts with detailed comments so you have ready to go utilities without having to paste bits of notebooks to piece together your code. 


## Pre-requisites

1. Install `lasair` python client

```
pip3 install lasair
```

2. A Valid Token (only for API / Kafka does not require a token)

You'll need to [register](https://lasair-lsst.lsst.ac.uk/register) to the Lasair platform so you can find your personal token on your [Profile](https://lasair-lsst.lsst.ac.uk/profile) page. 

**DO NOT SHARE THIS TOKEN WITH ANYOME**

## Have Any Suggestions? 

Feel free to fork this repository to propose changes, or open an issue to make a request. 

## How to get help?

If you have a question or need any help, you can find past questions or as a new one on the **[Community Forum](https://community.lsst.org/c/support/support-lasair/55)**.


![communityforum](tutorials/img/community_forum.png)


