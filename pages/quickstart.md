---
title: Quick-start Guide
layout: page
permalink: /quickstart
---

## Before you get started
{: .subheadline }

Check out our example site at [https://idahatiu.github.io](https://idahatiu.github.io), which has example items of several different types--photos, document scans, videos--so you don't have to start from scratch.

The 5 steps below will guide you through making a copy of our example site and customizing it for your community.

## Step 1
{: .subheadline }

**Create a new Github.com account by following this video: LINK**

1. Your Github username should be the name people will search for to find your community. For instance, a community group called "New City Community Archive" would choose the username "newcitycommunityarchive"
2. The "free" option will mean people can see, but not edit, the files that run your web site.


## Step 2
{: .subheadline }

**Make a copy of our template community-archive site by following this video:**

1. Visit [`https://github.com/idahatiu/idahatiu.github.io`](https://github.com/idahatiu/idahatiu.github.io)
2. Press the "Fork" button
3. Rename your repository `yourusername.github.io` (where *yourusername* is the username you chose when you created your Github account)

## Step 3
{: .subheadline }

**Customize the `_config.yml` with your community information by following this video: LINK**

1. Select the `_config.yml` from the list of files in your repository.
2. Click the pencil button to edit the file
   - Information about your community is on lines 42-63.
   - Choices for [colors]({{ site.baseurl }}/docs/colors/) and [fonts]({{ site.baseurl }}/docs/fonts/) are on lines 77-93.
3. Scroll to the bottom and use the "commit" button (Github's version of a "save" button)

## Step 4
{: .subheadline }

**Add your first item by following this video: LINK**

1. Open the "items" folder and look at one of the example items. Get a feel for what you need to gather about each item.
2. Each item should have its own unique filename.
   - We like `YYYY-MM-DD-ItemNo` (so the 4th item collected on May 15, 2022, would be `2022-05-15-004`
3. Each item will have its own information file in the `_items` folder (2022-05-15-004.md) and a photo in the `/assets/items/` folder (2022-05-15-004.jpg or 2022-05-15-004.png).

## Step 5
{: .subheadline }

**Publish your site using Github Pages by following this video: LINK.**

1. Find the "Settings" link on the top-right bar of your repository's info page
2. Find the "Pages" link on the left-hand side of your repository's settings page
3. Choose the "main" branch to publish in Github Pages