---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Managing Menus
description: Page description

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Managing Pages
        url: '/pages'
    next:
        content: HTML basics
        url: '/html'
---

<h2 id="menu-section">Menus</h2>
<p>Menus are simply a set of links to different parts of your site, or even to other websites. This set of links are grouped together into named menus.</p>
<ul>
    <li>Hover over the <strong>Content</strong> tab at the top.</li>
    <li>Select <strong>Menus</strong> from the drop down menu.</li>
    <li>On the right-hand-side of the page there is a button called <strong>Add a new menu</strong>, click this.</li>
</ul>
<p><img src="../images/new-menu.png" style="width:200px;"></p>
<p>You will then need to enter the details to add the menu. The fields are:</p>
<div class="callout callout--info">
    <p><strong>Reference</strong> This is the name of the menu.</p>
    <p><strong>Menu Type</strong> You can choose between <i>Links</i> or <i>Custom Content</i>.</p>
    <p><i>Links</i> - This is good to use for a naviagtion menu or submenu.</p>
    <p><i>Custom Content</i> - This is the same box you get when adding content to a page, and gives you the flexiblity to add any type of content that you want.</p>
    <p>The majority of menus will be linked-based, as <i>Custom Content</i> is mainly used to create content that you wish to behave like a menu.</p>
    <p><strong>Group</strong> Select the group that best fits the intention of the menu, for instance a menu that will feature links to pages about the company should go in the About group (if one exists).</p>
</div>
<h3 id="menu-subsection">Adding links</h3>
<p>A menu without links isn't very useful, so lets start bulding up a decent menu. Having just added a menu, or by editing an existing menu, click add a link at the bottom of the page.</p>
<p><img src="../images/add-link.png" style="width:100px;"></p>
<p>The browser will redirect to a new page, where you can set up a new link. You will be presented with the following fields:</p>
<div class="callout callout--info">
    <p><strong>Name</strong> This is the name of the menu i.e. Main Menu</p>
    <p><strong>Link to</strong>This allows you to definer where the link will go, you have a number of choices:</p>
    <ul>
        <li>Referer</li>
        <li>None</li>
        <li>External website</li>
        <li>Page from CMS</li>
        <li>Local path</li>
        <li>Custom MVC</li>
        <li>Legal disclaimer logout</li>
        <li>Legal disclianer</li>
        <li>File</li>
    </ul>
    <p><strong>Link target</strong>You can choose how you want your page to open.</p>
</div>
<p>As we want to link to our contact page, we choose <strong>Page from CMS.</strong> This allows us to select the pages we have created on the site.</p>
<p>(Image here)</p>
<p>Once you've clicked <strong>Contact us</strong> the link is ready to be saved. Click <strong>Save</strong> on the right-hand-side of the page.</p>
<div class="callout callout--danger">
    <p>Do not forget to hit save once you've finished to keep your changes.</p>
</div>
<h3 id="menu-subsection1">Ordering Links</h3>
<p>You may want your links to appear in a certain order, i.e. the homepage at the beginning and the contact page at the end.</p>
<p>This is easily possible from the menu edit view. Choose the menu you would like to edit then simply drag the links into the desired order.</p>
<p><img src="../images/reorder-link.png" width="400px" alt=""></p>
<h3 id="menu-subsection2">Submenus</h3>
<p>To create a submenu, you must create two menus:</p>
<ul>
    <li>A parent menu</li>
    <li>A submenu</li>
</ul>
<p>Edit the appropriate link in the parent menu, and click the <strong>Submenu</strong> tab. From here you can select the submenu.</p>
<p>If the CSS allows for it, submenus can have multiple layers. For example if you have a main menu at the top of the page, and under the <strong>About</strong> link, you want two menus to appear, <strong>Information</strong> and<strong>Contact</strong>, for example you must create four menus.</p>
<p>These menus would be the parent menu that has the original <strong>About</strong> link. The first submen which would feature just two links, <strong>Information</strong> and<strong>Contact</strong>, and then a separate menu for each of those links.</p>


