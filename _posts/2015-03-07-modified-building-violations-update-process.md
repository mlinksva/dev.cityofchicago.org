---
layout: post
title: Modified Building Violations update process
date: '2015-03-07T18:01:22-06:00'
tags:
- 22u3-xenr
- improvement
tumblr_url: http://chicagoportalstatus.tumblr.com/post/113011444050/modified-building-violations-update-process
---
We have upgraded the mechanism that updates the Building Violations dataset every day.  The main visible effect of this change is that the record counts for 2013-2015 have increased by about 80 percent.  We found some modifications and new building violations were not updating or being correctly added on the portal but are now doing a complete re-query of the source database and complete replace of the dataset each time we update.The last version of the dataset before the change in update mechanism is visible at https://data.cityofchicago.org/id/f4ic-vjbw.  This link may expire at some point so if you need the records, we recommend extracting and saving them.