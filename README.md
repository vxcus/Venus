# Venus

Venus was a semi-private Grim fork by vektus and Phit, written in Java and Kotlin which provided various detections for movement manipulations, combat or interaction automations for servers with 1000+ concurrent players.

## History of Venus
I started Venus as a skript anticheat back in 2020, which was horrible in terms of code (quite obvious, it was Skript). My goal was to learn more about checks in general. Back in 2022, so around 2 years ago, I started with the Java version of Venus, based on this anticheat **[Anticheat-Open-Source](https://github.com/DemonDxv/Anticheat-Open-Source) mainly to get in touch with Java anticheats and combat detections. The main focus wasn't really on the movement part, I only cared about the combat and scaffold part. This anticheat was maintained for 4 months and was able to detect a lot of clients back then due to flaws with the killaura rotations. In June 2023, I thought about forking Grim with a friend, who I know for almost 8 years since we were school mates before I moved. He really got me in touch with the interest of computer science in general. This project was designed to be a full anticheat solution with no additional anticheats. This anticheat had a lot of false positives, but I will talk about them in the mistakes part. This anticheat helped me a lot to get in touch with programming, so thanks to **[@DefineOutside](https://github.com/MWHunter)** for kinda bringing me back into Java programming. About 7 months ago, I added Kotlin support to the plugin, a programming language which I fell in love to due to the simple usage, especially the syntaxes. The syntaxes was one of the main reasons for switching. About 6 months ago the anticheat was at it's peak with a pretty stable version. We decided to recode the whole anticheat tho since the code was horrible even tho the 2.0 code was very horrible too and unable to maintain for anyone else.

## Goal of Venus
Back in 2023 I never thought that my anticheat is getting popular, since it was mainly operating on Gamster SkyWars, but back in Autumn 2023 some server got interested in what I'm doing there. I really don't know why, but a lot of cheating videos were advertising my anticheat. We decided to make Venus semi-private, only accessible for big servers. With no costs at all, while being not obfuscated. Therefore new customers **always** got a 6 month old version because it's very hard for me to trust new people.
But I think the main goal of Venus, and it's pretty hard for me to talk about that, was kind of therapy to me. The ability of programming helped me out of my depression that I face almost every winter, especially winter 2022 with the old anticheat base. The realization of ideas in code kinda made me happy, it was a feeling of "Hey, you finished something cool that came into your mind, good job!". 

## Mistakes
A lot of reasons resulted in the failure of Venus in 2024. It's very hard for me to talk about this topic since it involves a lot of private stuff.

### Horrible code style
As already mentioned, the code base was horrible and hard to maintain for anyone else besides of me. My main focus was to create checks and therefore I never cared about the code. Kind of back checks were still in version 2.0, but I will come back to this later on. The bad code resulted in version 2.0 with the goal of taking care of the code, mainly of simple documentation, so that my friends can actually understand what I'm doing there.

### Lack of motivation
A project like this is only maintainable when every part of the project is interested in it. Because of my baccalaureate and private events that happened recently, which resulted in a deep depression again. I kinda lost the motivation for the online world and I tried to leave it. But due to the dependence of customers, I tried to maintain it, even without any motivation. And this was a major mistake. It resulted in an even worse code since I only had the release in my mind. "You have to deliver something, fast" was in my mind. 

The lack of motivation in combination with depression and associated setbacks resulted in the development of the project being halted.

### Lack of transparency
After reflecting on the whole project, I should've been more transparent to the customers and the code. It resulted in a lot of misunderstandings. Venus had a backdoor, which was only used on Gamster to troll cheaters. But I haven't removed it for other customers, so it was always a part of it, which was never my intention. The backdoor was able to disable the whole anticheat and still give alerts to see if the livestreaming cheaters are flagging. Also, the code contained a simple name check, which enables debug alerts for developers, like Vulcan did. This obviously resulted in a lot of misunderstandings, which I'm very sorry for. It was never my intention to abuse the anticheat that way, even tho I removed it after the question came up. It also contained a command called "Access", which contained the name check aswell, giving us more information about the servers hardware.

## Future of Venus
After long brainstorming, I decided to make code optimizations and release the project for free on this GitHub page. It won't contain every check, but it will contain simple checks that should catch a lot of cheaters, even by the standards of Venus, a pretty good autoclicker check. I will release the jar probably when I have more interest so there will be no specific ETA. Probably this year tho.

## Final words / Thanksgiving

This project was the main reason why I managed my depression. Programming this is a kind of therapy, as already mentioned above. Maintaining this project all alone was definitely not possible. Therefore I want to thank some people and spread some love.
- **[@Phit420](https://github.com/Phit420) & JavaDouble:** Thank you for maintaining the project with me, even tho we had some parallels sometimes. It means a lot to me, much love to you. Thank you for realizing my dream of maintaining an anticheat like this.
- **[@officialMex](https://github.com/officialMex):** I would like to thank you for the inventory move check and a lot of help during the bad times of my live. Especially the last thing, means a lot to me. <3
- **[@Shadow192](https://github.com/Shadow192):** Thank you for trusting me with this plugin and helping me with any issues that I've faced.
- **Ducadamul:** Even tho we're in different communities, I would still like to thank you for reporting issues/bypasses that I've never faced. I don't hate you and this isn't meant to provoke you, I really valued it.

Thank you for reading this.
