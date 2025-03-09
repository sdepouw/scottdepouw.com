---
# the default layout is 'page'
icon: fas fa-book
order: 2
---

## Building a Game - Mathematics and Cheese

I've been wanting to program a game (with a UI beyond a terminal window or calculator screen) for quite a while. Early in 2025 I started messing around in [Godot](https://godotengine.org/), selecting it over others primarily for its C# support.

After completing a few tutorials, I started building a game in earnest. I commenced with a very basic concept of "the screen shows you a few options, and you have to pick the correct one." The inspiration stemmed from the mail sorting minigame in *The Legend of Zelda: The Wind Waker*. A simple-enough concept to emulate and a good way to start learning a bit about developing a game.

![A screenshot from the video game "The Legend of Zelda: The Wind Waker" showcasing the mail sorting minigame](/assets/pages/projects/wind-waker-mail-sort-screenshot.png)
_The more you sort the more rupees you earn!_

I started with simple number-matching: Show a number, and six numbers, and match as many as you can as fast as you can. Then I elevated it from "showing numbers" to "showing equations." Not long after, influenced in no small part by hanging out in the Discord for the [Squeakross video game](https://squeakross.cool/), I made the main character a mouse. Instead of earning money, the goal is to earn cheese. Hence the name, *Mathematics and Cheese* (said in the same way as one would say "macaroni and cheese.")

Since then I've been iterating, adding additonal features, game mechanics, and changing the overall user experience. A lot of this is just me experimenting with various game features or mechanics I've seen employed, to see if I can make them and to see how it's done. [I'm keeping the source code up to date in a public GitHub repository](https://github.com/sdepouw/mathematics-and-cheese/). You can even follow along my development process live by [viewing the Kanban board I've set up for myself](https://github.com/users/sdepouw/projects/3/).

### Play the Game In-Browser

After a non-specific number of new things get done, I [push the latest build of the game up to itch.io where anybody can play](https://doctorblue.itch.io/mathematics-and-cheese). Try to get the high score!

> While I really wanted to use C# to see how well I could employ best practices (and even unit testing) in a game development project, 
> unfortuantely [Godot 4 (the latest version) does not support exporting C# projects to the web at this time](https://godotengine.org/article/platform-state-in-csharp-for-godot-4-2/#web). So for *Mathematics and Cheese* I'm building it in Godot's custom language GDScript.
{: .prompt-info}

## The Legend of Zelda - Global Tracker for Speedruns

Bar

## This Site

I didn't have too much ambition in regards to this web site. I just wanted a place to be able to quickly update content, write blog posts, and more. After a bit of searching I landed on [Jekyll](https://jekyllrb.com/), using the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme. It took a couple hours from conception to going live, including domain name stuff, configuring the site, preparing GitHub and GitHub Pages, installing up Docker and related tools on my primary PC. Pretty quick all things considered!

Like all my projects [this one is maintained on GitHub](https://github.com/sdepouw/scottdepouw.com)!
