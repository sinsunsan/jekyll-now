---
published: true
title: Understanding mysterious google cloud authentication
---

Authentication is the more frustating part of google cloud at first. 
It seems really complicated with various system, a terminology that at first we do not understand. 

Let's list a few facts, we have undesrtood. 

* Accessing  the api guide [https://cloud.google.com/appengine/docs/admin-api/accessing-the-api](https://cloud.google.com/appengine/docs/admin-api/accessing-the-api)

the tutorial suggest you 
> Enable both the Google App Engine Admin API and Google Cloud Storage API in your Cloud Platform project:

So : 
* Api's are not enabled by default
* there is 2 concepts : 
   * google cloud storage : for storing static files
   * google app engine : to compute app like a virtual machine
   
When clicking on the enable [all apis  button](https://console.cloud.google.com/flows/enableapi?apiid=appengine,storage_component) 

I notice a panel that is about APIS

![API panel]({{site.baseurl}}/_posts/Screen Shot 2016-12-27 at 00.36.10.png)

That go to a page dedicated to all APIs. Not only the 2 mentioned, but more APIS that are in those 2 groups of APIS- storage and compute.

![Google cloud APIS]({{site.baseurl}}/_posts/Screen Shot 2016-12-27 at 00.34.18.png)

This page is also accessible via a side menu. 

![Gcloud side menu]({{site.baseurl}}/_posts/Screen Shot 2016-12-27 at 00.36.29.png)




   

