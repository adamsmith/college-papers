In reverse chronological order...


#### Friendship Prediction on Facebook (2005)
I worked on predicting friendship among Facebook non-friends for my graudate-level Machine Learning class project.  I crawled the MIT Facebook network, extracted structured profile and graph information, used it to train a classifier, and got some fellow students to give me real feedback.

At some point while crawling I submitted a malformed request, which deleted all of my Facebook wall posts...ah the sacrafices we make for the advancement of science!

<br/>

#### FromNowOn Web Archive System (2005)
This paper is a design document for a web archival system, much like web.archive.org.  It was a group project.  I ended up working with both of my teammates ([Rob Radez](http://www.linkedin.com/pub/rob-radez/7/7a3/833) and [David Pitman](http://hci4.me/)) at Xobni years later.

<br/>

#### Yellow Bus, A Universal Data Bus for BED Devices (2005)
This was a lot of fun to write.  The Beta processor was a CPU we designed from the gate-level up in a preceeding class, 6.003.  In this project we designed a USB-like bus for the CPU's.  From the paper:

> "This paper presents Yellow Bus, a single-master, flat architecture, polled bus for the Beta processor to use in communicating with other devices.  Because the bus is operated on the Beta memory lines it is important to minimize the amount of that address space occupied.  Two levels of addressing are used, session addresses and device IDs, to facilitate reliable device identification while minimizing the address space footprint of the system.  In addition, fairness with other user-mode programs is achieved by using a microkernel architecture; all I/O is performed in user-mode.  The interrupt-driven polling minimizes latency for reading data but also maximizes performance by minimizing unnecessary device polling.  These and many other features  make the Yellow Bus the right solution for any application requiring a high performance bus."

<br/>

#### Machine Learning in Practice - Book Proposal (2005)
I've always thought that machine learning is underused in industry.  As of 2013 that may be changing as people rally around "big data", but in 2005 I wanted to write a book written for people in industry who would like to bring applied statistics to their data problems.  I never submitted the proposal to any publishers.  My plan was to work on the book in the summer of 2006, but I ended up starting Xobni before then, so I never got around to it.

<br/>

#### Metrics for Counter-insurgencies (2004)
This paper isn't technical, but is pretty fun.  My humanities focus at MIT was on international security.  In this paper I look at how to measure the progress or lack there-of in a counter-insurgency, and then apply the framework to Iraq in 2004.

<br/>

#### Tracking Moving Devices with the Cricket Location System (2004)
I emailed a few MIT professors during my senior year of high school looking for research to do that summer, and I got lucky enough to work with [Hari Balakrishnan](http://nms.lcs.mit.edu/~hari/).  The research we did that summer led to this Mobisys 2004 paper, published during my freshman year.

The abstract:

> We study the problem of tracking a moving device under two indoor location architectures: an active mobile architecture and a passive mobile architecture. In the former, the infrastructure has receivers at known locations, which estimate distances to a mobile device based on an active transmission from the device. In the latter, the infrastructure has active beacons that periodically transmit signals to a passively listening mobile device, which in turn estimates distances to the beacons. Because the active mobile architecture receives simultaneous distance estimates at multiple receivers from the mobile device, it is likely to perform better tracking than the passive mobile system in which the device obtains only one distance estimate at a time and may have moved between successive estimates. However, an passive mobile system scales better with the number of mobile devices and puts users in control of whether their whereabouts are tracked.

> We answer the following question: How do the two architectures compare in tracking performance? We ﬁnd that the active mobile architecture performs better at tracking, but that the passive mobile architecture has acceptable performance; moreover, we devise a hybrid approach that preserves the beneﬁts of the passive mobile architecture while simultaneously providing the same performance as an active mobile system, suggesting a viable practical solution to the three goals of scalability, privacy, and tracking agility.

The paper has been cited > 300 times since its publication.  As lead author I was awarded the 2004 MIT EECS Award for Best Undergraduate Computer Science Research.  I open sourced the code and data behind the paper [here](https://github.com/adamsmith/indoor-tracking).