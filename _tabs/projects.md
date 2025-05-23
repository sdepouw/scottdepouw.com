---
# the default layout is 'page'
icon: fas fa-book
order: 2
---

## Building a Game - Mathematics and Cheese

I've been wanting to program a game (with a UI beyond a terminal window or calculator screen) for quite a while. Early in 2025 I started messing around in [Godot](https://godotengine.org/){:target="_blank"}, selecting it over others primarily for its C# support.

After completing a few tutorials, I started building a game in earnest. I commenced with a very basic concept of "the screen shows you a few options, and you have to pick the correct one." The inspiration stemmed from the mail sorting minigame in *The Legend of Zelda: The Wind Waker*. A simple-enough concept to emulate and a good way to start learning a bit about developing a game.

![A screenshot from the video game "The Legend of Zelda: The Wind Waker" showcasing the mail sorting minigame](/assets/pages/projects/wind-waker-mail-sort-screenshot.png)
_The more you sort the more rupees you earn!_

I started with simple number-matching: Show a number, and six numbers, and match as many as you can as fast as you can. Then I elevated it from "showing numbers" to "showing equations." Not long after, influenced in no small part by hanging out in the Discord for the [Squeakross video game](https://squeakross.cool/){:target="_blank"}, I made the main character a mouse. Instead of earning money, the goal is to earn cheese. Hence the name, *Mathematics and Cheese* (said in the same way as one would say "macaroni and cheese").

Since then I've been iterating, adding additonal features, game mechanics, and changing the overall user experience. A lot of this is just me experimenting with various game features or mechanics I've seen employed, to see if I can make them and to see how it's done. [I'm keeping the source code up to date in a public GitHub repository](https://github.com/sdepouw/mathematics-and-cheese/){:target="_blank"}. You can even follow along my development process live by [viewing the Kanban board I've set up for myself](https://github.com/users/sdepouw/projects/3/){:target="_blank"}.

### Play the Game In-Browser

After a non-specific number of new things get done, I [push the latest build of the game up to itch.io where anybody can play](https://doctorblue.itch.io/mathematics-and-cheese){:target="_blank"}. Try to get the high score!

> While I really wanted to use C# to see how well I could employ best practices (and even unit testing) in a game development project, 
> unfortuantely [Godot 4 (the latest version) does not support exporting C# projects to the web at this time](https://godotengine.org/article/platform-state-in-csharp-for-godot-4-2/#web){:target="_blank"}. So for *Mathematics and Cheese* I'm building it in Godot's custom language GDScript.
{: .prompt-info}

## The Legend of Zelda - Global Tracker for Speedruns

Speedrunners use a very nice tool named [LiveSplit](https://livesplit.org/){:target="_blank"} to track times whlie running a game. It's built in C#, [is open source](https://github.com/LiveSplit){:target="_blank"}, and is extensible via custom component creation.

I forked the [LiveSplit.Counter](https://github.com/LiveSplit/LiveSplit.Counter){:target="_blank"} component (which just counts up by 1 whenever you press a configurable key) and modified it to track globals. It's exactly like the counter, except it wraps from 0-9 (as the counter does in Zelda), and displays some extra information relevant to Zelda.

![A screenshot of LiveSplit highlighting the global counter](/assets/pages/projects/livesplit-global-counter.png)
_Note the green "Global" line, highlighting the current count as well as the next items that can drop._

I plan to migrate it to my primary GitHub account, but for now you can find this project up on my [other GitHub](https://github.com/DoctorBlue/LiveSplit.GlobalCounter){:target="_blank"}!

## This Site

I didn't have too much ambition in regards to this web site. I just wanted a place to be able to quickly update content, write blog posts, and more. After a bit of searching I landed on [Jekyll](https://jekyllrb.com/){:target="_blank"}, using the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy){:target="_blank"} theme. It took a couple hours from conception to going live, including domain name stuff, configuring the site, preparing GitHub and GitHub Pages, installing up Docker and related tools on my primary PC. Pretty quick all things considered!

Like all my projects [this one is maintained on GitHub](https://github.com/sdepouw/scottdepouw.com){:target="_blank"}!
