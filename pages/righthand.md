---
layout: page
title: RightHand Robotics
description: Piece-picking startup that I worked at out of college
---

Although much of my work at [RightHand Robotics](https://www.righthandrobotics.com/) can't be shared publically, here are some fun moments over the years.

---

Much of my time spent at RightHand was on various customer-focused projects, where we set up a system to work in a certain configuration, with specific geometries and integrations. Some examples of projects I worked on that got turned into public videos include [Apo integration](https://www.youtube.com/watch?v=8qjlQxN09zo) and the [NRF kitting system](https://www.youtube.com/watch?v=IylrLLJCQtY). The project pictured below was one of the more challenging projects, where we tried to place items into a warehouse feature called a putwall. The horizontal placement led to a variety of pathing issues, and at points I had to investigate the reachable workspace. The tooltip orientation's effect on reachability was particularly important for putwalls.

![Putwall](images/rhr-app1.jpg){: .img-mid}

![Putwall 2](images/rhr-app2.jpg){: .img-short}

![Pathing](images/rhr-app3.png){: .img-short}

![Reachability](images/rhr-app4.png){: .img-short}

---

In year two the company was just beginning to be more public, and I spent most of my time preparing systems for robust, sometimes specialized demos. This is one example of a demo system where we had to modify things to pick from non-standard containers in a warehouse store-and-present system. We demoed this system at Modex in Atlanta and I spent the show running around to keep a variety of systems running smoothly. For example, I worked on many of the demos shown [in this video](https://www.youtube.com/watch?v=a8MfBiu7v0Q) and [in this video](https://www.youtube.com/watch?v=xzoM95th4AI).

![Demo system](images/rhr-show1.jpg){: .img-mid}

---

One of my earliest jobs was to evaluate system speed and error rates over the course of long runs. It was important to harden the system, gradually working out the kinks so that it could run for hours or days without failure. It was especially difficult to match slow-settling and noisy scale output with a fast-moving system, which made it challenging to reliably classify actual errors (such as a flung item) with scale lag or noise. These tests really hammered home something that I think is a good engineering principle, which is to explicitly document moments and actions that you want to characterize instead of trying to back out the values that you care about from other system output.

![Rates over time](images/rhr-timing1.png){: .img-mid}

![Drop analysis](images/rhr-timing2.png){: .img-mid}

---

During a hackathon a co-worker and I modified our gripper so that it could draw pictures, which was a lot of fun. I wrote the image-to-shading code and we ran during a holiday party so that guests could automatically upload and draw their own pictures. Between arm pathing error and the mounting mechanism it wasn't the most precise drawing bot, but accurate enough to make entertaining images. This inspired a [company christmas video](https://www.youtube.com/watch?v=31FRsxF8XD0) which is pretty fun.

![Gripper attachment](images/rhr-draw1.jpg){: .img-mid}

![Drawing](images/rhr-draw2.jpg){: .img-mid}

![All drawings](images/rhr-draw3.jpg){: .img-tall}

![Minion render](images/rhr-draw4.jpg){: .img-mid}

---

At one point I played around with our stereo cameras and tried to take a person scan, but the stereo error leads to some pretty horrifying reconstructions. Later we investigated the stereo cameras and found that half-pixel level errors in stereo matching would geometrically lead to a 1-2 cm error at a meter, which essentially counts as unavoidable noise, so the scan probably couldn't have gotten much better with that camera without getting a lot closer.

![Body scan](images/rhr-stereo1.png){: .img-mid}

![Body scan zoomed](images/rhr-stereo2.png){: .img-mid}

![Face only](images/rhr-stereo3.png){: .img-mid}

---

My very first job as an intern at RightHand was a real privilege, I started back when the only people were the three founders. My first tasks as an intern were to do the electronics, control software, and visualization software for a direct-to-researchers robotic hand called ReFlex. These hands were tendon-driven with cast-rubber fingers, with a series of contact sensors built into the fingers. This hand continued for a few years but was eventually discontinued as RightHand grew into a warehouse-focused company.

![PCBs](images/rhr-reflex1.jpg){: .img-short}

![Assembled](images/rhr-reflex2.jpg){: .img-short}

![Visualizer](images/rhr-reflex3.png){: .img-mid}

![Electrical diagram](images/rhr-reflex4.jpg){: .img-mid}

![Test rig](images/rhr-reflex5.jpg){: .img-mid}