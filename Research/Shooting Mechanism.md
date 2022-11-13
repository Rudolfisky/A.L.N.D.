# Shooting Mechanism Development

## Why
The shooting mechanism is an core part of the demo-able aspect. 
<br/>
In other words, it would go a long way in achieving our desired impact.

## What are we developing
We are developing a way to dispense a nut over a distance of 1 to 2 meters.

## How
Using rapid prototyping (and a laser cuter <3) we will produce prototypes in order to learn how to successfully propel an cocktail nut over a distance.

# Result
With the use of quick prototyping and researching existing solutions, we came up with the following results.

## MK1
![SM LF MK1](../Media/prototype/SM%20LF%20MK1.jpg)<br/>

When we started on the shooting mechanism, we felt we needed to create the quickest, simplest P2P solution we possibly could. <br/>
using pre-existing knowledge of shooting mechanisms we decided to use a laser cuter and a rubber band to prototype the MK1.<br/>
Since the MK1 was a very simple "top of the head" idea, it meant there were some blatant flaws. <br/>
The rubber barely fits inside the device, let alone a cocktail nut.
<br/>

The image shows the rubber band surrounding the housing, but the original idea was to loop it around the the 2 thin front sticks. 
<br/>
The only reason the rubber band is positioned like it is in the photo is because it gave us a nice way to see the result without having to glue the contraptions. 
<br/>
This new rubber band position would help design the next iteration, the MK2.

## MK2

![SM LF both2](../Media/prototype/SM%20LF%20both2.jpg)

The MK2 (the one on the left) is the second iteration of the shooting mechanism. <br/>
After using the rubber band on the MK1 to hold it together, we realized that it made for a much more beneficial rubber band position. <br/>
Combining that with a shorter length, and thicker width, we realized the MK2.

![SM MK2 Use](../Media/prototype/mk2%20use.jpg)<br/>

### MK2 conclusion
The MK2 can manually be fired by pulling back the rubber, loading up a cocktail nut, and letting go of the rubber. Even though this process is very simple, it's still a fully functional Lo-Fi prototype that helped us in conveying our impact and researching further solutions.

## MK3
![SM MK3 1](../Media/prototype/MK3%201.jpg)<br/>
![SM MK3 2](../Media/prototype/MK3%202.jpg)<br/>
![SM MK3 3](../Media/prototype/MK3%203.jpg)<br/>

After the last iteration we decided to move away from the rubber band. After doing some research we came up with a couple solutions like using hydraulics, pneumatics, spring powered pistons. <br/>

### Research

![Nerf gun schematic](../Media/prototype/nerf%20gun%20insides.jpg)

The Nerf guns where specifically interesting to look at.<br/> The shooting mechanism seemed reliable, replicable, and automatable in comparison to alternative methods.

![Nerf gun screwed open](../Media/prototype/nerf%20gun%20screwed%20open.jpg)

After dismantling nerf guns to scavenge the shooting mechanism, I realized they wouldn't work. <br/>
The ones I had at home used a spring powered piston to push air into the Nerf dart, and considering the aerodynamics (or the lack thereof) of a cocktail nut, air simply wasn't an option.<br/> 
however, The spring powered system gave me an idea. 


### MK3 components
The MK3 consists of 2 additional components in comparison to the MK2: a spring powered cocking piece and a spring itself of course.

The cocking mechanism, to simply put it, is a stick with a couple holes and some would glued on the front. 

The hole in the back is used for pieces of wood to stop the mechanism from shooting out as well as automation capability. <br/>
We could attach a motor/servo powered piece of string to pull back the cocking mechanism. <br/>
The front has pieces of wood strategically placed in order to pull the spring back. <br/>
Last but not least, the stick has a little hole at the bottom that is used to lock the shooting mechanism once pulled back. 

Testing showed we needed to used 2 pieces for the long stick part or else the stick would break due to the amount of stress the spring would put on the little bottom notch.

### MK3 conclusion
This design was not without it's problems, but it definitely was a realistic design. <br/>
Not only was it functional, it also had the ability to be automated using electronics in the future.

## MK4
![MK4 front](../Media/prototype/MK4%20front.jpg)
![MK4 back](../Media/prototype/MK4%20back.jpg)

The MK4 is currently the last iteration of the firing mechanism and serves as a tested, demo-able, and marketable device.

### Changelog, what's changed?
Aside from the paintjob, the most obvious changes are the modified body shape and the new stand. 

The body shape was changed into a more `gun like` shape in order to prop the gun up in a 45 degree angle. <br/> This would be combined with a piece of wood that would've been propped below the new ribbed under barrel.<br/> this design seemed like it would've given us a lot of flexibility/configurability with the shooting angle.
<br/> After testing the ribbed under barrel we realized it was too unstable and flimsy too facilitate using the gun.

This is why we decided to design a stand that would fit on the bottom of the mechanism.<br/>
When combining the main shooting mechanism with the stand, one could theoretically shoot at an 45 degree angle.<br/>
This new stand would prove to be a bit flimsy as well, but the major upside is the more consistent shooting angles.

The cocking mechanism also had a few tweaks since the MK3.<br/>
First of all, we changed the safety precautions that where in place in the back of the stick.<br/> 
We changed the hole to a more structurally sound rectangle shaped hole.<br/> 
Through this hole we just stuck a piece of wood.

After testing how far we could propel cocktail nuts using the current cocking mechanism hole, we realized the shear velocity would've been enough to classify the project as a weapon.<br/> 
In order to get a more reasonable velocity we tried pulling back the stick and trying out certain positions to see what would give us the best performance, between 1 and 2,5 meters at a 45 degree angle.


In summary.
#### Body
- Gun like body
- Ribbed under barrel
#### Cocking mechanism
- Better safety
- New notch position for optimal distance and accuracy
#### New
- Gun stand  

### Testing
The testing went quite well.<br/> 
We first tried measuring the distance of **A.L.N.D.** by shooting it using the unmodified cocking mechanism. As we previously mentioned, it didn't go so well.<br/> 
After modifying the cocking mechanism to use less firing power, we got to shooting.

![nut field](../Media/prototype/nut%20field.jpg)

First we tried testing the accuracy of the **A.L.N.D.** by firing it a couple times and measuring the distance between points of impact.

Disregarding some misfires and taking into account the inconsistency of the cocktail nuts, I'd say we did pretty good.<br/> 
The nuts seemed to land within a radius of about a ruler (30cm).<br/> 
Ideally this result would've been less the 5cm, but we have to leave room for improvement.

After rigorous testing in the nut field, we decided it was time for a `live test`.

![MK4 test 1](../Media/prototype/MK4%20test%201.gif)
![MK4 test 3](../Media/prototype/MK4%20test%203.gif)

While testing we shot 10 nuts at our tester.<br/> 
5 where successful tests.<br/> 
As the tests progressed, the tester became more and more skilled at catching.<br/> 
This greatly improved the success rate.

Sadly, the only video we have of the test being successful is the POV footage from the tester.<br/> 
That being said, you can see how happy we are after seeing the results.

### Demo
![demo 1](../Media/demo/Demo%20setup%201.jpg)
![demo 2](../Media/demo/demo%20setup%202.jpeg)

The demo went really well.<br/> 
We managed to combine a good presentation (posters and cutouts) and the shooting mechanism.<br/> 
We put up some posters, used some mini displays for each iteration of the shooting mechanism, and setup a demo zone.

The demo zone (can be seen on the right) consists of an almost home like atmosphere.<br/> 
We used marked a spot on the couch and setup a laptop with video material in order to make the user feel like they're sitting at home relaxing the time away.

![GJ live demo](../Media/demo/GJ%20LD.gif)
![live demo](../Media/demo/demo%20vid.gif)
![live demo 2](../Media/demo/VID-20221104-WA0005%20fliped.gif)

Most demo's weren't successful in the sense that we correctly landed a cocktail nut in a users mouth, but we definitely got great results regarding our impact.<br/> 
After asking people what they thought about our product we got mixed responses.<br/> 
One thing was very clear for all of them though, no one wanted to buy it.<br/> 
Most believed it was to much of an gimmick.

### MK4 conclusion
At the end of the project I realized how much time I spent on making this device.<br/> 
The time spent making the shooting mechanism could've been spent on other things, especially now that it turns out I didn't have enough time to realize the automation part.<br/> 
This meant I had done done no programming and no electronical components. 

In hindsight, I'm happy with the functionality and the successful demo but sad because of the missing components.