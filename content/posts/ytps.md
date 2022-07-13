---
title: "YTPS: YouTube Terminal Search and Play"
date: 2022-07-11T18:08:30+05:30
draft: false
author: NoobScience
tags: ['Software', 'YouTube', 'Alt-SoftWare', 'CLI']
categories: ['Software']
series: ['AltSoftware']
searchHidden: false
---

# Introduction

Okay...I love CLI's and this was a huge achievement when I was learning to code in python and is one of the first production ready CLI I made. So this was a big one coming.

YTPS stands for YouTube Terminal Search and Play: It is a simple python script written in pure python and uses many community driven libraries that scrap the youtube website and put out the results to you in a super simple and easy way.

![YTPS 1](/images/ytps1.png)

# Installation

YTPS is quite easy to install and though might seem heavy, it is quite light (25mb) and it should work out of the box without any additional setup. One small hiccup is that you need a gpu accelarated terminal. Read More about it [Here](https://www.google.com/search?hl=en&q=what%20are%20gpu%20accelarated%20termin) and you must have [python](https://www.python.org/) installed.

## Pip Install

```shell
pip install ytps
```

This is the most easy way...Should take less then a minute. Here are a list of Modules Pip should install on a regular install.

![YTPS Module](https://newtoallofthis123.github.io/ytps/assets/imports.png)

## GitHub Installation

You can clone the repository directly from [github](https://github.com/newtoallofthis123/ytps)

```bash
git clone https://github.com/newtoallofthis123/ytps.git
cd ytps
pip install -r requirements.txt
```

You can also compile the script using [Nuitka](https://nuitka.net)

```bash
python -m nuitka --onefile --windows-icon-from-ico="icon.ico" --windows-company-name="NoobScience" --windows-product-name="YTPS" --windows-file-version=0.1 --windows-product-version=0.1 --windows-file-description="YouTube Terminal Search and Play" --python-arch="x86" __main__.py 
```

## Zip File

Okay...This is Nice and Portable.

### 🔽 Download The [ZIP](https://github.com/newtoallofthis123/ytps/releases/download/v.1.1/YTPS_Raw-v.1.1.zip)

# Usage

YTPS has a easy to use syntax which is quite fast and beautiful.

YTPS uses the [rich](https://rich.readthedocs.io/en/stable/introduction.html) library which makes sure you get the results in the most beautiful and modern way possible.

## Basic Usage

It is quite easy and fast

```bash
# Basic Search
ytps "search_term"
```

## Video Info

You get the up to date info about a video

```bash
# Video info from url
ytps --info "https://youtu.be/Y7MZqqcqWs4"
```

## Open Video Locally

You can open a youtube video locally on mpv with url (mpv only).

```bash
# Open Video Locally
ytps -p "https://youtu.be/Y7MZqqcqWs4"
```

## Open Video Locally with Search Term

You can also open the Latest Video of a given Search Term

```bash
ytps -o "https://youtu.be/Y7MZqqcqWs4"
```

## Channel Info

You can enter a Channel Search Term and get the info of the channel

```bash
ytps -c "NoobScience"
```

## About Page

See the About Page of YTPS

```bash
ytps -a ""
```

## Help Page

See the Help Page of YTPS

```bash
ytps -h
```

# YouTube ShowCase

## Watch [here](https://youtu.be/Y7MZqqcqWs4)

![YouTube ShowCase](https://i.ytimg.com/vi/Y7MZqqcqWs4/hqdefault.jpg?sqp=-oaymwEcCNACELwBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&amp;rs=AOn4CLAjtx6ve153EMd2NyXDBxC8Mp1Cxg%23center)

# License

## [MIT License](https://newtoallofthis123.github.io/license)

> Copyright (c) 2022 Noob Science

# Conclusion

So overall I would highly recommend you try YTPS and YTSpider and I am sure you would love it. That's all for today. 

## 👋🏻 Have a Great Day
