#SAE #Reflection #213/P1
# Mid Project Reflection
> [!info]- 
> Include the mid-project reflection with your project submission. In 250 words, address each of the prompts with examples from your project:
> - How you developed your technical skills and knowledge
> - How have you improved your workflows and processes
> - How you developed your communication and collaboration skills

I was super excited for this project first hearing about it, been waiting forever to finally jump into some game audio stuff. 
After playing around with both Unity & FMOD I could see how more nuanced you can be with FMOD than with the stock Unity audio engine, as well as having a much more audio centric UI compared, I decided I would go down the path of doing all my audio through FMOD and integrating it into Unity. 
This however ended up being probably the worst decision I could have made in the end, for 2 main reasons in particular. 

- Deciding to do all of the Audio work through FMOD left me with the mentality to not really look into the game & Unity till later. This culminated in me recording & crafting a whole bunch of audio that I ended up feeling wasn’t quite right for the game, from the sound aesthetic to the art design. As well as this, I should have gone in with the ideal that I first have to learn the core basics of Unity and it’s audio engine, before I can start learning and figure out a plug-in & different system for it 
- Secondly I put in a bit of work already so once I hit a bit wall where I couldn’t seem to get FMOD integrated, instead of cutting my losses taking what was usable and moving forward, I instead got stubborn and tried to brute force my way with it. This ended up with me not only wasting a lot of time, but actually stonewalling myself out of actually using that project file. I messed it up that bad that I couldn’t even backtrack FMOD out of the project, and with neither of the audio engines working I I didn’t have any audio period, which in the end had me having to start again from scratch. 

Other than all that, once I started to find my footing in Unity I really enjoyed it, having a full Eureka moment when I accidentally found out you can move the camera freely around the map with WASD (while holding right click) 

---
# Project Completion Reflection
> [!info]- 
> > In 250 words, address each of the prompts with examples from your project:
> - How you appraised the overall success of the project
> - What obstacles you faced and how you overcame them
> - How you will improve your skills for future projects

Following up from my previous reflection, coming to the project completion I definitely think I was way too ambitious with what I had in my head for the project, in comparison to what was outlined. From having a vision of using FMOD to achieve everything with the audio and implementing it into Unity, to having every if not the majority of the sounds either recorded & sound designed myself. 
This even from the start was a inherently a bad idea, as firstly never using Unity or FMOD before, I’d first have to learn how these apps & systems work, after that I could then use the knowledge & skills to achieve the results that I wanted. That coupled with the insane task of Recording / Sound Designing everything myself, would have been impossible under the time frame, especially when I have multiple other projects as well as work to worry about. 
What I should have done instead is right from the start, use the resources that they provided for us (Sound-snap / Soundly) to collect all of the audio assets that I might have needed, process them to sound aesthetically coherent, then implemented them into the game through Unity, learning along the way how that system works. And given the time, my stretch goal should have been to use Unity, maybe some scripting, to implement more complex audio systems, or to go back and replace some of the audio with assets that I recorded / designed myself. That way I could have gotten the core deliverables and ideas down and handed in *ON TIME* as well as mitigating a lot of the unneeded stress I put on myself.

Other than those setbacks, I still in the end really enjoyed the Project, and think that I ultimately did some pretty good work in the sense of implementation, I think that everything sounds quite cohesive, balancing is good, and the couple of times that I actually designed some sounds myself I think were a good addition to the overall project (maybe not the campfire music ambience though / feels a bit too “on the nose”).
For the future to streamline the process I think that I would see if there’s a way to create some templates or something, to add in groups of components with just a click - As once I figured out how to have audio trigger open a collision, It was a bit tedious to continually have to add in the same 3 components with the exact parameters, only having to change which of audio asset was being used.

I am a little upset at the end of the day that I never ended up figuring out how to properly implement FMOD and the work I’d done there into Unity, as I feel like I had a lot of ideas of how I could make the audio even more immersive (ideas that could have been done using FMOD. But at the end of the day, it is what it is. Moving forward though I definitely think I’ll have to spend some time learning more of how the backend implementation works for game engines, maybe find some community games and try re-doing the audio, or even looking through the SAE Marketplace for people working on game projects that need audio.

**Updating my reflection notes upon completing the project -** What was said previously is even more relevant now, as with almost any project, things will go wrong, things will mess up. I happen to have managed to some how lock myself out of my Unity project. 
While doing the final polishes of the project (balancing sound, swapping out some assets, etc.) the Unity Editor crashes. Not really that surprising as I’ve had a lot of issues with Unity crashing along the way of this project - (a good lesson in saving as frequently as possible). Though this time when I tried to open it back up, it would load and then hang upon “Initial Asset Database Refresh” I thought maybe its just working extra slow, so I left it and came back around and hour or 2 later. No dice. 
After looking through forums and Googling everything I could, re-installing Unity Editor, Unity HUB, replacing the assets I could remember working on last, checking if any files I had added recently were corrupted, I couldn’t get it working. I knew it was something to do with the project itself as I could open a new project inside Unity, just not my current project. 
After almost a week of constantly trying to fix it, and wanting to give up completely, I found the culprit. I accidentally when added in new assets, renamed an old file - adding in a ‘/‘ at the end.
Removing it finally got everything working again, which in hindsight seems kind of buggy that such a simple mistake can basically soft lock you out of your project, without even an error message or code from Unity.

![[../../../../../../../../../3. Resources/DEPRICATED/🧹OBSOLETE Resources/Media/Pasted image 20230507034308.png|Pasted image 20230507034308.png]]

![[../../../../../../../../../3. Resources/DEPRICATED/🧹OBSOLETE Resources/Media/Pasted image 20230507034317.png|Pasted image 20230507034317.png]]

### Sidenote
Ran into a few problems when trying to capture gameplay footage - for some reason after building the Game App there was a noticeable 'whomp' sound in the background, and after picking at it for hours I couldn't even locate the source of the sound 
	I ended going to a backup version - redoing the tweaks & re-building the Game App - no mysterious ghost 'whomps' anymore

Although after this I had issues capturing audio when screen recording - already had blackhole installed from years ago, but a re-install wasn't successful. 
	I ended up having to grab a different tool "Loopback Audio" where I managed to get audio recording with video - HOORAH!

