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
      <h2 class="section-heading">Growing Thrivable Social Fabric</h2>
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
      <h2 class="section-heading">Technical Overview: Draft--March 2024</h2>
      <hr class="light">
    </div>
    <div class="row text-left">
      <div class="col-lg-12 col-md-12">
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
        <p><img style="width:100px;float:left;margin-right:10px;" src="/images/moss_icon.png"/> Download and try Moss, our reference implementation of a Frame for The Weave</p>
      </div>
      <div class="col-lg-8 col-md-8">
        <p><strong>Browsers</strong>, like Firefox and Chrome are the programs that allow you to, well, browse the documents served up by web servers.
        </p>
        <p><strong>Frames</strong> are the programs that let you create, access and weave together Holochain hApps into the social fabric of The Weave</p>
      </div>
      <div class="col-lg-12 col-md-12">
        <p class="screenshot-image aligncenter"></p>
      </div>
      <h3 class="aligncenter">Capacities</h3>
      <div class="col-lg-6 col-md-6">
        <p> A core feature of the weave is the the ability for groups to pick the fit-for-purpose tooling that's appropriate for each group, and, if desired
        add specific new tools as purpose and needs evolve.</p>
        <p>Assets generated in one Capacity can be linked to and embedded in other Capacities creating an functionality centric computing environment rather than the usual application centric model.</p>
        <p>Here are a number of Capacities that have allready been developed that you can use to get a feeling for the power of this approach.</p>
        <ul class="capacities">
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/vines.svg"> <strong>Vines: </strong> Provides the usual chat functionality: topics, channels, attachments, mentions, etc.</li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/slate_icon.svg"> <strong>Slate: </strong> Provides real-time collaborative drawing. Fully featured diagrams and drawing tools based on the <a class="linkable" href="https://excalidraw.com/">Excalidraw</a> open-source library.</li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/notebooks_logo.svg"> <strong>Notebooks: </strong> Provides real-time collaborative editing of MarkDown documents. Includes syntax-highlighting, version history, and more.</li>
          <li> <img class="capacity-logo" src="/images/kando_icon.png"> <strong>KanDo: </strong> provides robust KanBan functionality with commenting, assignments, labels, categories, checklists and more. </li>
        </ul>
      </div>
      <div class="col-lg-6 col-md-6">
        
        <ul class="capacities">
          <li> <img class="capacity-logo" src="/images/talking-stickies_icon.png"> <strong>TalkingStickies: </strong> provides real-time stickies-boards for ideation, meeting agendas, retros, etc... </li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/converge.png"> <strong>Converge: </strong> allows stakeholders to shift focus from outcomes to refining a set of criteria that has maximal support. Using this list, they can evaluate and refine proposals to meet those broadly supported criteria.</li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/whosin.png"> <strong>Who's In?: </strong> enables users to propose collective actions or events. With it, anyone can suggest a joint action or event, which other people can agree to on the contingency that every necessary role is filled. This allows group action to grow effortlessly from idea to reality without anyone having to worry about its viability.</li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/snapmail_logo.jpg"> <strong>SnapMail: </strong> provides email-like in-group messaging with attachments, replies, etc.</li>
          <li> <img class="capacity-logo" src="https://lightningrodlabs.org/projects/where_logo.png"> <strong>Where: </strong> provides a generalized grammar for creating shared maps for groups to see the emergent "whereness" of each other across those them, as well as the grammatics to self-evolved these spaces and how to represent "location" in them.</li>
          <li> <img class="capacity-logo" src="/images/gamez_icon.svg"> <strong>Gamez: </strong> provides a place to design and play arbitrary board games.</li>
        </ul>
      </div>


      <p class="aligncenter"><br /><a href="https://github.com/lightningrodlabs/we/releases/tag/we-alpha-v0.10.7" class="btn btn-default btn-xl sr-button">Download</a></p>

    </div>
  </div>
</section>
