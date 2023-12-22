---
title: "Projects"
# meta title
meta_title: "Trung's Projects"
# meta description
description: "Trung's side projects"
# save as draft
draft: false
---

{{< toc >}}

## Personal Website (this)
{{< image src="images/myimages/personalWebsite.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

{{< button label="GitHub" link="https://github.com/trungvu08/trungvu08.github.io" style="solid" >}}
{{< button label="Demo" link="https://trunghvu.com/" style="solid" >}}

Tags: Hugo, Tailwind CSS, GitHub Pages, NodeJS, GO, PostCSS, PurgeCSS, AutoPrefixer, Hugo Modules, Markdown, Prettier, Jshint

My own website created with Hugo and TailwindCSS using an open-source template and hosted on GitHub Pages.

Creating a personal website is not only great for marketing, but it's also just great for getting more expereince with different languages and frameworks quickly. I became interested in building a website after my intern buddy, Mihir, convinced me to buy a custom domain. I bought the domain through Google Domains for $12/yr (and hope it'll stay at that price), but since Squarespace acquired Google Domains in Sep 2023, I don't know if they'll mark up the price. Anyways, I didn't want to create the website from scratch because I have no artistic/design ability, so I looked for a template to use. I went through two templates from two of the most popular static site generators, [Jeykll](https://jekyllrb.com/) and [Hugo,](https://gohugo.io/) and found a nice template on Hugo. There are tradeoffs to using either Jekyll or Hugo, but both are easy to get into and for my purposes, the tradeoffs aren't a big deal. This [article](https://draft.dev/learn/hugo-vs-jekyll) sums up the tradeoffs quite well.

One of the pros of using a template is that you don't need to develop from scratch. That being said, one of the cons is you are given a large codebase with lots of files you don't understand. The template I found was nice, but it didn't have lots of documentation on how to use it. I was adding/deleting code here and there to slowly figure out what was connected to what, but I ultimately decided to do some tutorials and learn how Hugo worked. The tutorials by [Magsther](https://medium.com/@magstherdev/github-pages-hugo-86ae6bcbadd) and [4BES.NL](https://4bes.nl/2021/08/29/create-a-website-with-hugo-and-github-pages/) were quite helpful. With that, I became modifying the template to fit my needs and got my website up and running. I hosted it on [GitHub Pages](https://pages.github.com/) because its free. GitHub Pages automatically builds your site when you push changse to your repo, so that created less hassle for me. To serve my site from my custom domain rather than GitHub's default of user_name.github.io, I modified the repo settings and also did some configuration on Google Domains. This [GitHub article](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) summarizes the process quite well.

After 2 weeks of having the website, I got bored of the template and it's lack of flexibility, so I moved to a different template called [Hugoplate](https://github.com/zeon-studio/hugoplate). This one had more documentation, support, and flexibility. By modifying certain files, I fit the website to my needs. More specifically, I modified .html files to add more buttons on the homepage so I can link both my resume and CV. I also modified .scss files to prevent overflow text in the Experience page from being clipped. This was actually quite fun because on top of learning how scss worked, I had to use inspect element to figure out how the classname of the parts I wanted to modify the styling of. Beyond this, I modified various .md, .json, and .toml files to change the site layout and add my personal information.

I don't think there's going to be a point where I just stop improving/developing this website. There's a lot I want to do with it such as utilizing the Blog page. Also, my resume and CV change practically every month, so I need to come back and update links anyways. But yeah, I strongly encourage people to build a personal website. It's fun, useful, and also a cool flex!

<hr>

## Pong!
{{< image src="images/myimages/pong.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

{{< button label="GitHub" link="https://github.com/nnguyendinh/FPGA_pong" style="solid" >}}
{{< button label="Demo" link="https://youtu.be/lv8HEuWlOhk" style="solid" >}}

Tags: Verilog, FPGA, VGA

This project was done in collaboration with my buddies [Annie Xiang](https://www.linkedin.com/in/anniexiang01/) and [Nathan Nguyendinh.](https://www.linkedin.com/in/nathan-nguyendinh/) We created a 2-player game called PONG!. The game was programmed using Verilog through Xilinx ISE and is displayed on a VGA monitor while the scoreboard is displayed on the seven-segment display of the DE10-LITE FPGA. In this game, players compete against each other using paddles to hit a ball into the opponent’s goal. The ball bounces off the top and bottom sides of the VGA monitor. Each player has two buttons to move their paddle up and down. If a player lets the ball enter their goal, the current round ends with the opposing player gaining a point. Both players play up until one player gets 5 points or the game is reset using the RESET button.

The game is displayed on a VGA monitor and starts upon pressing the START button. Before the START button is pressed, a color gradient is displayed as the start screen. Upon starting the game, two paddles appear on the right and left of the screen and a ball appears in the center of the screen, moving towards a player. Additionally, a scoreboard appears on the seven-segment display starting with 0 points for each player. Player 1 and player 2 can each move their respective paddle using the buttons on external button modules. Each player has a button to move their paddle up, and another button to move their paddle down.

The players compete to bounce the ball with the paddle alternatingly and have their opponent miss the ball. Each time the ball is hit, its speed will increase until it reaches a maximum speed which it will then sustain. The round ends when one player misses the ball and it hits their side (i.e. Player 1 misses the ball and it hits anywhere on the left side of the screen). The player who misses the ball and lets it pass through their side loses the round. When a round ends, the scoreboard updates, giving 1 point to the winner and 0 points to the loser.

A new round starts with the ball appearing in the center of the screen and moving towards a player. The game will continue until a player gets 5 points, in which the game will go back to the start screen. At any point in the game, a player can push the RESET button to restart the game and scoreboard at any point and time, going back to the start screen and setting both scores back to zero.

To get a better visual understanding of what was just described along with a more detailed explanation, please watch our demo video linked above!

<hr>

## Uniqueness Test
{{< image src="images/myimages/uniquenessTest.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

{{< button label="GitHub" link="https://github.com/trungvu08/uniquenesstest" style="solid" >}}
{{< button label="Demo" link="https://trunghvu.com/uniquenesstest/" style="solid" >}}

Tags: ReactJS

React project hosted on GitHub pages that is a family-friendly version of the popular Rice Purity test.
<hr>

## Digital Audio Visualizer
{{< image src="images/myimages/dav.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

<!-- {{< button label="GitHub" link="/" style="solid" >}}
{{< button label="Demo" link="/" style="solid" >}} -->

Tags: SystemVerilog, FPGA, VGA

System that visualizes frequencies of audio signals on VGA monitor with SystemVerilog and an FPGA. I also recreated the Flappy Bird video game where users control bird movement using FPGA.
<hr>

## Wordle PLUS
{{< image src="images/myimages/wordlePlus.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

{{< button label="GitHub" link="https://github.com/trungvu08/Wordle-PLUS" style="solid" >}}
<!-- {{< button label="Demo" link="/" style="solid" >}} -->

Tags: ReactJS, MongoDB, NodeJS, ExpressJS

Remake of popular web-based word game Wordle using MERN stack. Builds on Wordle by allowing game to be played with 4, 5, or 6 letter words and giving unlimited plays a day with a random word each time.
<hr>

## Fitness Form Protection Tool
{{< image src="images/myimages/fitnessFormProtectionTool.jpg" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="false" >}}

<!-- {{< button label="GitHub" link="" style="solid" >}} -->
{{< button label="Demo" link="https://youtu.be/kuaJNQWbsLo" style="solid" >}}

Tags: C, IoT, Machine Learning, STM32

Internet of Things (IoT) system created using C, EmbeddedML Neural Network, and STMicroelectronics SensorTile which hosts a STM32L4 microprocessor, accelerometer, and gyroscope. The IoT system uses 2-state motion analysis to determine if a user has properly executed simple exercises (Russian twist, hip rises, sit ups).
<hr>
