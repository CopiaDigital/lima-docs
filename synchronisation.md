---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Synchronisation and Microsites
description: Synchronising and creating microsites

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Menus
        url: '/menus'
    next:
        content: Managing Groups
        url: '/menus'
---

<h2 id="sync-section">Adding a new Microsite</h2>
<p>If you would like to synchronise your current content to a new microsite then you will need add a new site:</p>
<ul>
    <li>Hover over the <strong>Settings</strong> tab at the top.</li>
    <li>Select <strong>Sites</strong> from the drop down menu.</li>
    <li>On the right-hand-side of the page there is a button called <strong>Add a new site</strong>, click this.</li>
</ul>
<p><img src="../images/new-site.png" style="width:200px;" alt="Add a new site button"></p>
<p>You will then need to enter details of the new site. The fields are:</p>
<div class="callout callout--info">
    <h5 style="margin-top:1.1rem;">Details tab</h5>
    <p><strong>Name</strong> This is the admin name of the microsite.</p>
    <p><strong>Module</strong> This is the name of the folder in <i>sites/</i>. This is the same as the name without any spaces.</p>
    <p><strong>Title</strong> This is the Public title used in site meta.</p>
    <h5 style="margin-top:1.1rem;">Domains tab</h5>
    <p><strong>Domain</strong> If you would like the micorsite to point to another domain you can add it here.</p>
</div>
<div class="callout callout--danger">
    <p><strong>Please note</strong> If you are adding a new domain, please contact <a href="mailto:support@copiadigital.co.uk" target="_blank" rel="noopener">Copia</a> to set up the serverside.</p>
</div>

<h2 id="sync-section1">Synchronisation</h2>
<p>Lima includes the ability to create different versions of the site, such as a <strong>draft</strong> verison, dependant on how the site has been set up.</p>
<p>When signed in as an administrator, you will see this bar at the top of the browser:</p>
<p><img src="../images/admin-bar.png" style="width:500px;" alt="CMS Admin bar"></p>
<p>You can use this bar to switch between versions of the site, i.e. between <strong>Main</strong> and a <strong>Microsite, Live</strong> mode and <strong>Draft</strong> mode, and if applicable, different <strong>language</strong> versions of the site.</p>

<h3 id="sync-subsection">Synchronising to a new site</h3>
<ul>
    <li>Hover over the <strong>Synchronisation</strong> tab at the top.</li>
    <li>Select <strong>Everything</strong> from the drop down menu.</li>
</ul>
<p>You will be presented a screen with two options:</p>
<h5>Merge</h5>
<div class="callout">
    <p>A merge will copy across all changes between versions, but leave any new items (pages, menus, etc) in the destination variation.</p>
</div>
<h5>Replace</h5>
<div class="callout">
    <p>Performing a replace will create an exact copy, removing any changes you might have made on the destination variation.</p>
</div>
<p>Once you select either <strong>Merge</strong> or <strong>Replace</strong>, you then can specify what you are synching and where to.</p>
<p><img src="../images/sync-options.png" alt="Sync options"></p>
<div class="callout callout--info">
    <p><strong>Mode</strong> This determines which draft of the site you will be synchronising from (<i>Live</i> is set by default).</p>
    <p><strong>Site</strong> This determines which version of the site you will be synchronising to (<i>The main site</i> is set by default).</p>
    <p><strong>Language</strong> This determines which language version you will synchronise.</p>
</div>
<p>Once you have set your preferences, click on the <strong>Synchronise</strong> button.</p>
<p><img src="../images/sync.png" style="width:150px;" alt="Syncronise button"></p>








