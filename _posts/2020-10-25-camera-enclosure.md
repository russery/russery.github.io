---
title: DIY Webcam Enclosure
header:
    teaser: /assets/images/2020/enclosure_glamor_shot.jpg
tags:
- 3D Printing
- webcam
- COVID
---
As with many folks over the last year, I've been working from home since the start of the COVID pandemic. I unfortunately didn't have a webcam back in March for the new world of Zoom meetings, so I hopped on Amazon to find one. Finding one that was in stock at that time and not outrageously expensive was more difficult than I had anticipated and I ended up buying a bare-board USB camera: [ELP 2.8-12mm Varifocal Lens Camera](https://www.amazon.com/gp/product/B00SPBWM0M/).

This camera doesn't have an enclosure or any way to hold it in position. I ended up using some rubber bands to hold it to a miniature Joby tripod that I had hanging around:

[![Camera and Tripod](/assets/images/2020/webcam_with_tripod.jpg){:width="50%"}](/assets/images/2020/webcam_with_tripod.jpg)
[![Rubber Bands](/assets/images/2020/rubber_bands.jpg){:width="25%"}](/assets/images/2020/rubber_bands.jpg)
<!--more-->

## The Design

As you can see in the photos, this solution was left much to be desired in terms of long-term durability. I decided to give 3D printing an enclosure a shot and whipped up a quick solution in FreeCAD. Demonstrating my lack of CAD skills, I managed to end up with this masterpiece:

[![Weird Science](/assets/images/2020/how_does_cad_work.jpg){:width="50%"}](/assets/images/2020/how_does_cad_work.jpg)

I managed to get it sorted out and into something a bit more reasonable, after thirty minutes and a bit of cursing:
[![Enclosure CAD](/assets/images/2020/case_iso.png){:width="50%"}](/assets/images/2020/case_iso.png)

I had planned on using a brass threaded insert for the tripod attachment on the bottom and using threadforming M2 screws into the small holes in the camera mounting bosses.

My friend John who works for a high-end 3D printing and prototyping company offered to print the case for me. He got the design into a bulk print of [PA12](https://www.fastradius.com/resources/polyamide-12/) that his company had running, and even said he could print the tripod threads into the design instead of adding a threaded insert after the fact. Unfortunately the M2 screw holes were too small to print, so those got scrapped on the final design.

## The Goods

Fast forward to a few days later - I got the finished parts back and gave it a test fit:

[![Enclosure First Fit Check](/assets/images/2020/enclosure_glamor_shot.jpg){:width="50%"}](/assets/images/2020/enclosure_glamor_shot.jpg)

Woohoo! It was a perfect fit. Here are a few more shots, with the #2 screws drilled and tapped in place to hold the camera instead of the kapton tape I'd used on the fit-check:
[![Front View](/assets/images/2020/front_view.jpg){:width="50%"}](/assets/images/2020/front_view.jpg)
[![Rear View](/assets/images/2020/rear_view.jpg){:width="50%"}](/assets/images/2020/rear_view.jpg)
[![Iso View](/assets/images/2020/side_angle_view.jpg){:width="50%"}](/assets/images/2020/side_angle_view.jpg)

## Design Files

Here's the design if you'd like to use it for this camera:<br/>
[camera_case.FCStd (1.1MB FreeCAD)](/assets/files/camera_case.FCStd)<br/>
[camera_case.step (1.2MB Step file)](/assets/files/camera_case.step)

Note that these files don't include the tripod threads and still have the M2 screw holes that weren't present in the final print.