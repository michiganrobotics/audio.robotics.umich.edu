---
layout: post
title:  "Computer vision"
date:   2022-05-18 14:29:23 -0400
audio_id: audio location 330
accordion: 
  - title: audio transcript
    content: "<p>If you turn and look out over the atrium, you can see chairs, tables, perhaps students, windows, trees outside, maybe passing cars. How might a robot do the same, and more importantly, make sense of it all enough to interact with or avoid all these things?</p><p>Researchers in COG: the Cognitive Robotics Lab create mathematical models and algorithms to capture the information from video and images, such as what objects are in a video, where they are, and what is happening with those objects. This allows machines, such as home-service robots and autonomous vehicles, to better understand what they are seeing and the best way to react.</p><p>In describing a paper that improved a computer’s ability to separate out objects from a video, Professor Jason Corso explains that humans and computers do best by working together.</p><p>This is an instance of a type of method called hybrid intelligence in which a human is involved in the machine learning process with a computer system so that the sort of value from both pieces can be combined together. So computers are very good at repetitive tasks, tasks for which there's not much variability, whereas humans are excellent at adapting to new situations, to challenging task things that they haven't really understood before.</p><p>So when we want to train a deep learning or machine learning system, we need to provide examples. Examples typically are in the form of images or sets of images or videos or sets of videos. And if all we did was say, Here are my videos, and we wanted to have the machine learning system trained, it would get confused by the background and the lighting or the variability of the motion.</p><p>Annotation is the process of asking humans who are experts in this case to provide the actual boundaries or boxes around them, in this case, boundaries around the content that we want to focus on so that we can basically point the deep learning system or computer vision system at the appropriate content that we want it to focus on. There are two core applications that come to mind immediately when we think about applications of, in particular, video object segmentation.</p><p>One is in-home robotics, so service robotics, maybe there's an elderly person around the home and they eventually will have a service robot alongside them to help make coffee, make a sandwich, make sure they're getting the appropriate medicine in order for a robot to interact with household objects. In this way, the robot needs to have a very refined, detailed, segmented, segmented type of representation over its visual field.</p><p>And so this is a direct application or direct tool for that application. The second application that comes to mind is autonomous driving, right? So we want to have safe autonomous vehicles on the road. We don't want them to get into accidents, cause accidents hit a pedestrian, for example. So for that, they need to calculate free space where no object is present.</p><p>But free space is a hard thing to actually directly find because we can always see the road or see the horizon, right? So in this case, we can have them detect the objects and draw boundaries around the objects and then induce the free space by using a video object segmentation type method.</p>"
---

<div class="audio-player">
   <!-- this is where the player will be injected -->
</div>

![Results showing how a computer interprets the objects in an image](/assets/images/330-computer-vision.jpg)

Robots can sense their surroundings in many ways, but how do they make sense of them? Researchers in COG: the Cognitive Robotics Lab create mathematical models and algorithms to capture the information from video and images, such as what objects are in a video, where they are, and what is happening with those objects. This allows machines, such as home-service robots and autonomous vehicles, to better understand what they are seeing and the best way to react.


{% include accordion.html %}

## Related
* [Vision dataset: YouCook2](http://youcook2.eecs.umich.edu/explore)
* [Start-up: Voxel51](https://voxel51.com)




<script type="text/javascript">

 const player = new Shikwasa({
   container: () => document.querySelector('.audio-player'),
   audio: {
     title: 'Computer vision',
     artist: 'audio location 330',
     cover: '/assets/images/330-computer-vision.jpg',
     src: '/assets/audio/330-computer-vision.mp3',
   },
   // fixed: {
   //   type: 'static',
   // }
 })

 </script>
