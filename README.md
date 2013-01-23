college-papers
==============

In reverse chronological order...


#### Friendship Prediction on Facebook (2005)
* Class: graduate level Machine Learning
* Description: when Facebook was still very young, I crawled the MIT Facebook network, extracted structured information from profiles and photos, and used that data to predict friendship among non-friends.
* Notes: at some point during crawling I submitted a malformed request, which deleted all of my Facebook wall posts.  Ah the sacrafices we make for the advancement of science!

<br/>

#### FromNowOn Web Archive System (2005)
* Class: Computer Systems
* Description: a web archive system, similar to web.archive.org
* Notes: this was a group project.  Both group mates, [Rob Radez](http://www.linkedin.com/pub/rob-radez/7/7a3/833) and [David Pitman](http://hci4.me/), ended up working at my startup Xobni years later.

<br/>

#### Yellow Bus, A Universal Data Bus for BED Devices (2005)
* Class: Computer Systems
* Description: from the paper..

	"This paper presents Yellow Bus, a single-master, flat architecture, polled bus for the Beta processor to use in communicating with other devices.  Because the bus is operated on the Beta memory lines it is important to minimize the amount of that address space occupied.  Two levels of addressing are used, session addresses and device IDs, to facilitate reliable device identification while minimizing the address space footprint of the system.  In addition, fairness with other user-mode programs is achieved by using a microkernel architecture; all I/O is performed in user-mode.  The interrupt-driven polling minimizes latency for reading data but also maximizes performance by minimizing unnecessary device polling.  These and many other features  make the Yellow Bus the right solution for any application requiring a high performance bus."

* Notes: this was a lot of fun to write.  The Beta processor was a CPU we designed in software from the gate-level up in a preceeding class, 6.003.  In this project we designed a USB-like bus for the CPU's.

<br/>

#### Machine Learning in Practice - Book Proposal (2005)
* Class: None (extracurricular)
* Description: I've always thought that machine learning is underapplied in industry.  (As of 2013 it seems that's finally starting to change.)  So I wanted to write a book focused on people in industry who would like to bring applied analytics to their data problems.
* Notes: I never submitted it to any publishers.  My plan was to work on the book in the summer of 2006, but I ended up starting Xobni before then, so I never got around to it.

<br/>

#### Metrics for Counter-insurgencies (2004)
* Class: US Military Power
* Description: This one isn't technical, but is pretty fun.  My humanities focus at MIT was on international security.  In this paper I look at how to measure the progress or lack there-of in a counter-insurgency, and then apply the framework to Iraq in 2004.

<br/>

#### Tracking Moving Devices with the Cricket Location System (2004)
* Class: None, this was a Mobisys 2004 paper I was lead author on
* Description: How does one design the state estimation algorithms for an indoor tracking system?  What architectures are possible and which are best?
* Notes: I open sourced the code and data behind the paper [here](https://github.com/adamsmith/indoor-tracking).