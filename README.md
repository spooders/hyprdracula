![image](https://github.com/SpooDerS/hyprdracula/assets/26696457/5e18671a-99e3-45fb-acb0-7abb3f14c835)

![image](https://github.com/SpooDerS/hyprdracula/assets/26696457/e6dd708d-93e9-4c7d-9a51-d932be0c8c12)
![image](https://github.com/SpooDerS/hyprdracula/assets/26696457/19eb22a9-b51d-443d-98a6-d0e43f15760d)
![image](https://github.com/SpooDerS/hyprdracula/assets/26696457/1c614c19-24b8-4a07-a4d5-5cf368469fc5)


# hyprdracula
(sorry for poor formatting I dont know how readmes work here)
I have added this for inspirational purposes and this is not a guide but rather how my personal rice is built. 
Some things might rather work inconsistently if you straight up copy and paste my stuff so I will try to cover most things I did although I cant cover it all. this is gonna be pure text explination and might not cover everything at all and not concrete. its a bad guide but im lazy and did not intend to upload this anyways but something is better than nothing right?

also pro tip that does not have anything to do with this config but more about discord and hyprland, I highly recommend using discord-screenaudio from the aur because as of my knowladge it is the only discord client that can use noise suppression with screen sharing plus audio (although the audio is streamed on mono not stereo I think but its a lot better than other clients in my opinion)

Also wanted to say I took inspiration from here https://www.youtube.com/@lakfdjlskad and practically based the theming of the waybar from their config: https://github.com/jas3333

I installed hyprland directly along with plasma with the archinstall script after setting up my system just so you know in case it does make a differense but I have no idea. 

Then I installed all other things like the qt stuff, rofi, dunst, rofi-emoji etc I dont have all the packages I installed becuase I have not written them down since I kinda frankensteined together all of this anyways and some might be bothered the way I did things which is understandable but I did not have all day so bear with me. 

then some vital things I did was to install ios emojis, I did it by following this guide: https://gist.github.com/win0err/9d8c7f0feabdfe8a4c9787b02c79ac51

though I dont understand how to use those commands so for instance in the first step I just downloaded the AppleColorEmoji.ttf and copied it over to /usr/share/fonts/
then I followed thorugh step 2 as it is on the guide but on the third step idk what kinda cli tool that is but figured out that you should just make the dir with the first command then inside there make the fonts.conf file with only the xml syntax that was provided. then ran step 4 and boom I had ios emojis. they are truely the only emojis in my opinion. 

Now furthermore you might notice that the waybar text is dark for the title bar. im not sure exactly what theming system that text follows but I know its some kind of system wide something idk if its gtk or whatever. trigger warning for people with immense ocd about this but yes, I went into kde plasma, opened the apperance tab and went into every single aspect of apperance and downloaded some dracula themes for stuff like decorations etc I dont know what they are called but whatever. and boom white text. you might know a lot better way of doing this so let me know if you know how. 

and I also browsed around the hyprland wiki to see whatever I else needed which I would highly recommend instead of following my "guide" that is all over the place. 
Also for screenshot tool which is equivalent to the one on Windows where you hold WindowsKey + Shift + S to select an area and having it copied into the clipboard immediatly I installed wl-clipboard slurp and grim and boom ez screenshots. 

there is some bloat that I actually dont even know if it still works where on top if you were playing spotify it would display a fancy animated tag in the middle of the waybar but I think either it only works for some spotify clients or if my configuration is broken for that. Also while we are on the topic of waybar, if you want weather indicator to work (on the top left after the workspaces) you will have to input your own api key (which you need to input in the weather.py script in the waybar config directory. also make sure to set the appropriate LAT and LON for your location)for a weather service that I dont remember the name of so your on your own there but it was not that hard to find out. I also installed font awesome and I think the audio indicator and internet icons use to the right of the waybar. 

you might have noticed that you cannot spawn a terminal with my configs unless you already use zsh. this is because in my alacritty.yml config I made it use zsh and I dont have the system shell set to it becuase it would look weird in the tty with the FiraCode Nerd font which you should make sure you have installed otherwise some stuff will look goofy. unless you are gonna install and use another font which you probably will idk. 

I probably missed some stuff but tried to cover the most essential things. good luck

Key combinations to know about: 
meta + space --- app launcher
meta + e     --- emoji selector that copies to the keyboard (though I dont remember if I had to do any deeper setup than just the config file)
