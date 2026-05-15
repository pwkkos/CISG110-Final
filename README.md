# CISG110-Final

## Devlogs

### Week 12

One issue I encountered while putting together my game this week was that when I would run my game, the disable kick function would show an error message stating "Invalid assignment of property or key 'process\_node' with value of type 'int' on a base object of type 'Nil'". I didn't know what that meant at first so in order to figure out the issue, I rewatched the part of the tutorial that went over everything related to that specific code while retracing all of my steps. After retracing my steps, I found out that when I was dragging the "kickRight" node over to the inspector to assign it to the "kick right" variable, it didn't actually get assigned and was left empty (which I wasn't aware of before). I was able to fix it easily by just manually assigning the node to the variable instead of dragging it, but it was a very easy mistake to overlook.

### Week 13

An issue I encountered this week was an error message stating, "Invalid assignment of property or key 'emmitting' with the value type 'bool' on a base object of type 'CPUParticles2D' after i kicked a prop. What I did to find the issue was I look over the written code from the tutorial and compared it to mine to check for any differences. I found out that the issue with my code was just that i spelt "emitting" incorrectly; I spelled it as "emmitting" with two m's instead of one, which was an easy fix but really shows just how important it is to know how to spell when coding.

### Week 14

An issue I encountered this week was that my kicking animation wouldn't play whenever I pressed space/enter. I figured that it was likely because I wasn't putting my code for playing the animation in the correct spot so what I did was I asked my brother (who knows how to code) to help me figure out what to change, which is kind of cheating...but it was late and i just wanted to have my homework done fast and I was able to resolve the issue by placing the code for playing the animation as a part of the if statement with the other \_anims.play so that the kick anims was the if statement, the idle anims was the elif, and the walk anims was the else. After that change, I was able to get the animation to play normally.

### Week 15

Although I do find game development very enjoyable, I don't think I see myself pursuing it in the future as it is not something I'm entirely passionate about (however I will still probably continue game design as a hobby). In the future, I plan to pursue a career in engineering or anything math related since it is one of my favorite and strongest subjects as of now. My plan on reaching this goal is continuing to take more rigorous classes and dual enrollment courses during my high school years and participating in activites that can help to strengthen any skills, ensuring that I am fully prepared for the future. This class really helped me experience how a fully asynchronous course is like and I felt like I was able to manage my time fairly well. I tried to keep a consistant schedule of when to finish my assignments so I never felt overwhelmed with this class and my other classes' work, allowing me to maintain a good balance of work and free time throughout the entire school year. I hope that my free time driven motivation and the need to keep a scheduled routine will continue to help me become successful both now and in the future. 

## Open-Source Assets

* [Ninja cat sprites](https://opengameart.org/content/cat-fighter-sprite-sheet)
* [Item sprites](https://ipixl.itch.io/pixel-art-items-part-1)
* [Interior tilesets](https://rcpstd.itch.io/interior-tileset-asset-pack-16x16)
* \[Rat sprites](https://carysaurus.itch.io/rat-sprites)

