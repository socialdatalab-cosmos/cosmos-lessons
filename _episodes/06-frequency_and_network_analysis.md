---
title: "Frequency and network analysis"
teaching: 10
exercises: 5
questions:
- "How do we use network and frequency views in the COSMOS?"
objectives:
- "Understanding frequency and network analysis with COSMOS."
keypoints:
- "COSMOS provides frequency analysis with Twitter data to help us analyse and draw conclusions."
- "COSMOS provides network analysis that gives the opportunity to understand social network structure, the role of key players, communities, etc... "

---

# Lessons
***
## 1. Frequency Analysis
In the frequency view, COSMOS provides 3 types of frequency analysis on a *daily*, *hourly* and *minutely* basis. You can change the time interval by clicking the slider underneath each graph. This view helps to spot tweet spikes over time easily. Chart sliders can be used to create a subset of data around these spike dates.

See the example of frequency view below:

![Frequency view](../fig/Frequency-view.png){:height="400px" width="900px"}

***  
#### You can also watch a youtube video by clicking the image below for all frequency processes with COSMOS.
***

<iframe width="560" height="315" src="https://www.youtube.com/embed/2dFHog_ClBQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 2. Network Analysis

COSMOS provides network analysis with Twitter data. It can currently be used to visualize `retweets` and `mentions` networks. 
![Network view 1](../fig/network-view-main.png){:height="300px" width="800px"}

These network views aim to identify prominent users and their level of influence in the network.  They also show information flows in social media e.g. thoughts of prominent users on a particular event, topic or product. Both views (retweet and mention) help to visualize the connection and interaction between users. Network graphs can be created based on the network metrics `degree`, `closeness` and `betweenness`. Network metrics can be selected from the drop-down menu on the right-hand side of the page. COSMOS also gives the filter option to adjust nodes and label visibility on the network chart. Using the sliding chart on the right panel, you can adjust how the network chart looks.   
![Network view 2](../fig/network-view-retweets.png){:height="400px" width="800px"}

Similar to other views in COSMOS, you can create subsets *'Ctrl (Command) + Click'* on multiple nodes to focus on and deeply analyse the network for specific accounts. 

***  
#### You can also watch a youtube video by clicking the image below for all frequency processes with COSMOS.
***

<iframe width="560" height="315" src="https://www.youtube.com/embed/xo4M1-nSKCM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> ## Exercise
>
> Create a subset of a collection that contains at least 2 users that affect the network for a specific event.
>  
{: .challenge}

