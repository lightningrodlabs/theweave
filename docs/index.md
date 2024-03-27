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
          <li>enables collaboration with fit-for-purpose group-ware <i>Tools</i></li>
          <li class="text-faded">makes "own-your-data" real by design</li>
          <li>allows you to search all of your data across the groups you are part of</li>
          <li class="text-faded">grows with network-effects as <i>Tools</i> are added to the ecosystem </li>
          <li>centers groups and their members, not large corporate silos</li>
        </ul>
      </div>
      <div class="col-lg-6 col-md-6">
        <div class="about-image"></div>
      </div>
      <div class="col-lg-6 col-md-6">
        <p >What we now call "The Web" was the result of three critical new open standards: HTML, HTTP and the URL.  These allowed anybody to publish documents and link to them from other documents.  The advent and Javascript and CSS made it so these documents were both beautiful and as functional as any computer program.  </p>
        <p> But none of those open standards enabled creation and management of <i>social context</i> by groups.  So, that critical function has become siloed into the big corporate websites:  Facebook holds group's "Page", GitHub holds your code, GSuite holds your collaboration tools.</p>
        <p ><a class="linkable" href="https://holochain.org"><i>Holochain</i></a> is an open standard that delivers creating small functioning units of <i>social context</i>, in a way that is both scalable, and decentralized.  To that we now add the <strong>Weave Interaction Pattern</strong>, an open standard for creating, searching, linking and organizing these <i>social context</i> units into complex social fabric that yields "The Weave".</p>
      </div>
      <p class="aligncenter"><br /><a href="#technical" class="btn btn-default btn-xl page-scroll sr-button">Go Deeper</a>
      &nbsp;<a href="#tryit" class="btn btn-default btn-xl page-scroll sr-button">Try It</a></p>
    </div>
  </div>
</section>
<section class="bg-dark" id="technical">
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
      <p class="aligncenter"><br /><a href="#tryit" class="btn btn-default btn-xl page-scroll sr-button">Try It</a><a style="margin-left:10px;" href="#developers" class="btn btn-default btn-xl sr-button page-scroll">Develop The Weave</a></p>
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
      <div class="col-lg-8 col-md-8">
        <p><strong>Browsers</strong>, like Firefox and Chrome are the programs that allow you to, well, browse the documents served up by web servers.
        </p>
        <p><strong>Frames</strong> are the programs that let you create, access and weave together Holochain hApps into the social fabric of The Weave</p>
      </div>
      <div class="col-lg-4 col-md-4">
        <p><img style="width:100px;float:left;margin-right:10px;" src="/images/moss_icon.png"/> <a class="linkable" href="https://github.com/lightningrodlabs/we/releases/tag/we-alpha-v0.11.6" >Download and try Moss</a>, our reference implementation of a Frame for The Weave</p>
      </div>
      <div class="col-lg-12 col-md-12">
        <p class="screenshot-image aligncenter"></p>
      </div>
      <h3 class="aligncenter">Tools</h3>
      <div class="col-lg-6 col-md-6">
        <p> A core feature of The Weave is the the ability for groups to pick the fit-for-purpose tooling that's appropriate for each group, and, as desired add specific new tools as the group's purpose and needs evolve.</p>
        <p>Assets generated in one Tool can be linked to and embedded in Assets created by other tools.  This creates an
        "asset-centric" computing environment rather than the usual application centric model.</p>
        <p>Here are a number of Tool capacities that have already been developed that you can use to get a feeling for the power of this approach:</p>
        <div class="capacities">
          <div> <a href="https://github.com/lightningrodlabs/vines"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/vines.svg"> </a><span><strong>Vines: </strong> Provides the usual chat functionality: topics, channels, attachments, mentions, etc.</span></div>
          <div> <a href="https://github.com/lightningrodlabs/slate"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/slate_icon.svg"> </a><span> <strong>Slate: </strong> Provides real-time collaborative drawing. Fully featured diagrams and drawing tools based on the <a class="linkable" href="https://excalidraw.com/">Excalidraw</a> open-source library.</span> </div>
          <div> <a href="https://github.com/lightningrodlabs/notebooks"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/notebooks_logo.svg"> </a><span> <strong>Notebooks: </strong> Provides real-time collaborative editing of MarkDown documents. Includes syntax-highlighting, version history, and more.</span> </div>
          <div> <a href="https://github.com/holochain-apps/kando"><img class="capacity-logo" src="/images/kando_icon.png">
            </a><span> <strong>KanDo: </strong> provides robust KanBan functionality with commenting, assignments, labels, categories, checklists and more. </span> </div>
          <div>
            <a href="https://github.com/matthme/unzoom"><img class="capacity-logo" style="height: 50px; width: 50px; border-radius: 5px; margin-right: 10px;" src="/images/presence_icon.png" alt="presence">
          </a><span><strong>Presence:</strong> provides video conferencing with screen sharing </span> </div>
        </div>
      </div>
      <div class="col-lg-6 col-md-6">
        <div class="capacities">
          <div> <a href="https://github.com/holochain-apps/talking-stickies"><img class="capacity-logo" src="/images/talking-stickies_icon.png"> </a><span><strong>TalkingStickies: </strong> provides real-time stickies-boards for ideation, meeting agendas, retros, etc...</span> </div>
          <div> <a href="https://github.com/lightningrodlabs/converge"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/converge.png"> </a><span><strong>Converge: </strong> allows stakeholders to shift focus from outcomes to refining a set of criteria that has maximal support. Using this list, they can evaluate and refine proposals to meet those broadly supported criteria.</span></div>
          <div> <a href="https://github.com/lightningrodlabs/whos-in"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/whosin.png"> </a><span> <strong>Who's In?: </strong> enables users to propose collective actions or events. With it, anyone can suggest a joint action or event, which other people can agree to on the contingency that every necessary role is filled. This allows group action to grow effortlessly from idea to reality without anyone having to worry about its viability</span> </div>
          <div> <a href="https://github.com/glassbeadsoftware/"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/snapmail_logo.jpg">
            </a><span> <strong>SnapMail: </strong> provides email-like in-group messaging with attachments, replies, etc.</span> </div>
          <div> <a href="https://github.com/lightningrodlabs/where"><img class="capacity-logo" src="https://lightningrodlabs.org/projects/where_logo.png">
            </a><span> <strong>Where: </strong> provides a generalized grammar for creating shared maps for groups to see the emergent "whereness" of each other across those them, as well as the grammatics to self-evolved these spaces and how to represent "location" in them.
            </span> </div>
          <div> <a href="https://github.com/holochain-apps/gamez"><img class="capacity-logo" src="/images/gamez_icon.svg">
            </a><span> <strong>Gamez: </strong> provides a place to design and play arbitrary board games.</span> </div>
          <div> <a href="https://github.com/lightningrodlabs/tables"><img class="capacity-logo" src="/images/tables_icon.svg">
            </a><span> <strong>WaterTable: </strong> provides ability to create database-like tables for collecting and viewing data.  Think of this as an "AirTable" clone!</span> </div>
          <div> <a href="https://github.com/lightningrodlabs/calcy"><img class="capacity-logo" src="/images/xylem_icon.svg">
            </a><span> <strong>Xylem: </strong> provides real-time collaborative spread-sheets based on the <a class="linkable" href="https://github.com/dream-num/univer">Univer</a> open-source library.</span> </div>
        </div>
      </div>
      <p class="aligncenter"><br /><a href="https://github.com/lightningrodlabs/we/releases/tag/we-alpha-v0.11.6" class="btn btn-default btn-xl sr-button">Download Moss</a><a style="margin-left:10px;" href="#developers" class="btn btn-default btn-xl sr-button page-scroll">Develop The Weave</a></p>
    </div>
  </div>
</section>

<section class="bg-dark" id="developers">
  <div class="container">
    <div class="row text-center">
      <h2 class="section-heading">Developing The Weave</h2>
      <hr class="light">
    </div>
    <div class="row text-left">
      <div class="col-lg-6 col-md-6">
        <h3 class="aligncenter">Our Methodology</h3>
        <p>Many deep infrastructure projects are built by creating a very detailed specification, and then building to it.  With The Weave, this is not our way.</p>
        <p>Instead we have built Moss, as a reference frame and discovery tool to understand what needs to exist inside The Weave, as we begin using it organically ourselves to grow our own social fabric.  The concepts described in this website emerged over time, beginning from what was at first just understood as a <a href="https://eric.harris-braun.com/blog/2022/07/26/id-390">distributed groupware</a> platform, and are now solidifying into a more formal protocol with the <strong>Weave Interaction Pattern</strong> described above.</p>
        <p>We expect this to become more formalized over time, but for now we want it to emerge from the
        experience and needs of actual groups using this framework.  Thus we are not prematurely creating a "hard-spec" of for the WIP</p>
        <p>We expect very soon to open a Group that uses a Tool in development called <a href="https://github.com/holochain/how">How</a> to "dog-food" the landing of the WIP spec.</p>
      </div>
      <div class="col-lg-6 col-md-6">
        <h3 class="aligncenter">Building Tools</h3>
        <p>Coding a Weave Tool is a matter of updating a standard Holochain hApp in a few ways.</p>
        <p>It's trivial (a 5 minute task) to simply update your hApp to run in the context of a Weave Frame,
           this just involves getting the <code>AppAgentClient</code> from the Frame instead of building it directly
           using the <code>holochain-client</code> library. </p>
        <p>It takes a little more work to add support for other aspects of the Weave Integration Protocol, but each of these affordances (searching, linking, embedding, creating) can be added one piece at a time and are not a heavy lift. Detailed instructions for how to add  can be found in the <a class="linkable" href="https://www.npmjs.com/package/@lightningrodlabs/we-applet">client npm package docs</a></p>
        <p>But the easiest approach may simply be to clone any one of the projects above (clicking on the icon takes you to each Tools's github repo), and modify it to your needs.  That's what we often todo!</p>
      </div>
    </div>
  </div>
</section>
