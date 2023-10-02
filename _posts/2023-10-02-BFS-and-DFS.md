---
title: BFS and DFS
author: Bhoomeendra 
date: 2023-10-02
category: Jekyll
layout: post
---
## Problems
### [417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/description/)

This is a must do problem because we have to thing in reverse of what question is suggesting. The qustion is as follow we have hills and each hill has a hight x give in the martix heights and the hills are surrounded by the two oceans Pacific and atlantic. When it rains on hills the water can go down the hill is its neighbhours are of same heights of less that its heights. We have to identify the hills from which the water can flow on both the oceans. At first we may start to think the we can do dfs from each cell if it reaches both the sides then we have reached. This solution will also work but will not be the most clean. What we can think is reverse the flow from ocean to the mountains. So now it becomes easer to think. Because we already know the starting points of the dfs search which are the hills adj to the oceans. Now we can think of ascending of water up the hill. We can do this for both the oceans seprately and mark all the hill that can be reached and then take the intersection of that. 
