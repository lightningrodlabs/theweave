---
layout: default
title: Home
image: /images/moss_mushrooms.jpg  
navigation_weight: 1
permalink: /
description: ""
---
<header>
  <div class="header-content">
    <div class="header-content-inner">
      <h1 class="home-heading">The Weave</h1>
      <hr style="margin-bottom: 1em;"/>
      <p class="header-text">Open standards and implementations for growing thrivable social fabric.</p>
      <p><a href="#about" class="btn btn-primary btn-xl page-scroll">Explore</a></p>
    </div>
  </div>
</header>
<section class="bg-primary" id="about">
  <div class="container">
    <div class="row text-center">
      <h2 class="section-heading">Growing Healthy Social Fabric</h2>
      <hr class="light">
    </div>
    <div class="row text-left">
      <div class="col-lg-6 col-md-6">
        <p>The social fabric of complex and healthy societies is composed of many interlocking social agreements involving many community subsets.</p>
        <p> We provide a grammar and implementation of a set of open protocols and standards for spinning up all kinds of small social agreement units and weaving them together in a meaningful and easy to use way.</p>
        <p style="font-weight:bold; font-size:180%;">The Weave:</p><ul>
          <li class="text-faded">allows groups to embody their social context without any centralized infrastructure</li>
          <li>enables collaboration with fit-for-purpose group-ware <i>Capacities</i></li>
          <li class="text-faded">makes "own-your-data" real by design</li>
          <li>allows you to search all of your data across the groups you are part of</li>
          <li class="text-faded">grows with network-effects as <i>Capacities</i> are added to the ecosystem </li>
          <li>centers groups and their members, not large corporate silos</li>
        </ul>
      </div>
      <div class="col-lg-6 col-md-6">
        <div class="about-image"></div>
      </div>
      <div class="col-lg-6 col-md-6">
        <p >What we now call "The Web" was the result of three critical new open standards: HTML, HTTP and the URL.  These allowed anybody to publish documents and link to them from other documents.  The advent and Javascript and CSS made it so Web Browsers could these documents could be both beautiful and as functional as any computer program.  </p>
        <p> But none of those open standards enabled creation and management of social context by groups.  So, that critical function has become siloed into the big corporate websites:  Facebook holds group's "Page", GitHub holds your code, GSuite holds your collaboration tools.</p>
        <p ><a class="linkable" href="https://holochain.org"><i>Holochain</i></a> is the first new open standard that enables creating small functioning units of social context.  To that we now add the <i>Weave Interaction Protocol</i>, an open standard for creating, searching, linking and organizing these units into complex social fabric that yields "The Weave".</p>
      </div>
      <p class="aligncenter"><br /><a href="#deeper" class="btn btn-default btn-xl page-scroll sr-button">Go Deeper</a>
      &nbsp;<a href="#tryit" class="btn btn-default btn-xl page-scroll sr-button">Try It</a></p>
    </div>
  </div>
</section>
<section class="bg-dark" id="deeper">
  <div class="container">
    <div class="row text-center">
      <h2 class="section-heading">The Details</h2>
      <hr class="light">
    </div>
    <div class="row text-left">
      <div class="col-lg-10 col-md-10">
      {% capture my_include %}{% include_relative paper.md %}{% endcapture %}
      {{ my_include | markdownify }}
      </div>
      <p class="aligncenter"><br /><a href="#tryit" class="btn btn-default btn-xl page-scroll sr-button">Try It</a></p>
    </div>
  </div>
</section>

<section class="bg-primary" id="tryit">
  <div class="container">
    <div class="row text-center">
      <h2 class="section-heading">Moss</h2>
      <hr class="light">
    </div>
    <div class="row text-left">
      <div class="col-lg-4 col-md-4">
        <p><strong>Browsers</strong>, like Firefox and Chrome are the programs that allow you to, well, browse the documents served up by web servers.
        </p>
        <p><strong>Frames</strong> are the programs that let you create, access and weave together Holochain hApps into the social fabric of The Weave</p>
        <p><img style="width:100px;float:left;margin-right:10px;" src="/images/moss_icon.png"/> Download and try Moss, our reference implementation of a Frame for The Weave</p>
      </div>
      <div class="col-lg-8 col-md-8">
        <div class="screenshot-image"></div>
      </div>

      <p class="aligncenter"><br /><a href="https://github.com/lightningrodlabs/we/releases/tag/we-alpha-v0.10.7" class="btn btn-default btn-xl sr-button">Download</a></p>

    </div>
  </div>
</section>
