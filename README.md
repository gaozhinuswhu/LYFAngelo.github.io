This project is used to manage the personal homepage of Professor Gao. The website can be visited by both [gaozhinuswhu.com](https://gaozhinuswhu.com) and [gaozhinuswhu.github.io](https://gaozhinuswhu.github.io). The domain analysis of the website has been stored on Aliyun.

The template was forked from [Academicpages Github](https://github.com/academicpages/academicpages.github.io), to find the guidance and get more information for this template, please visit [Academicpages](https://academicpages.github.io).

## Modify Content
In order to modify the contents of different pages, please visit the following directories separately:

Personal information: [_config.yml](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/blob/master/_config.yml)

Introduction and core paper presentation: [_pages/about.md](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/blob/master/_pages/about.md)
For adding some pictures on the core paper presentation part, please upload them in the fold [images](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/tree/master/images) first, rename the pictures and then use them in the refer to these names in the page.

Publication: [_pages/publications.md](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/blob/master/_pages/publications.md)

CV: [_pages/cv.md](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/blob/master/_pages/cv.md)

If you would like to modify the content, you can edit online directly.


## Create Content
To create a new content for the mapsite, you should add the content name in the configuration file for the top menu, which is in the  [_data/navigation.yml](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/blob/master/_data/navigation.yml). Then create the profile for the page in the [_pages](https://github.com/gaozhinuswhu/gaozhinuswhu.github.io/tree/master/_pages) and add the title below in the profile.

```
---
layout: archive
title: "Your Name 1"                // "Your Name 1" is the name of the column displayed on the web page
permalink: /Your Name 2/            // "Your Name 2" is the fixed sub-domain name required for access
author_profile: true
redirect_from:
  - /Your Name 3                    // "Your Name 3" is the redirect file corresponding to navagation
---

```

Then you can wirte the main content of the page.
