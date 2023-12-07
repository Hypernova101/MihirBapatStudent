---
toc: true
comments: false
layout: post
title: Partner Posts
description: Ansh's first post on Mihir's Website
type: hacks
courses: { compsci: {week: 2} }
---

<p style="animation: bounce 2s ease infinite; background: linear-gradient(to right, #C9B1FF, #FFCAF2, #FFB2B1, #FFF3AD, #BCFFBC, #A2EDFF);-webkit-text-fill-color: transparent; -webkit-background-clip: text;"> ___________________________________________________________________________________________________________</p>

<div style="background: linear-gradient(to right, #35bde7, #0064cf); -webkit-text-fill-color: transparent; -webkit-background-clip: text; text-shadow: 0px 0px 30px gray; text-align: center;">
    <p id="content1"></p>
</div>

<br>

<div style="background: linear-gradient(to right, #DB0CEB, #F1D7A9); -webkit-text-fill-color: transparent; -webkit-background-clip: text; text-shadow: 0px 0px 20px white; text-align: center;">
    <p id="content2"></p>
</div>

<style>
    @keyframes bounce {
        0%, 20%, 50%, 80%, 100% {
            transform: translateY(0);
        }
        10%, 30%, 60%, 90% {
            transform: translateY(-30px);
        }
        40%, 70% {
            transform: translateY(-15px);
        }
    }
</style>

<script>
    function typeWriter(text, i, id) {
        if (i < text.length) {
            document.getElementById(id).innerHTML += text.charAt(i);
            i++;
            setTimeout(function() { typeWriter(text, i, id); }, 20);
        }
    }
    var text1 = "Throughout my life, I've experienced many things. Pain, triumph, melancholy. I've seen many things, heard many things, all of which had led to one thing: CSSE. See, my progress in HTML and cascading style sheets has been exponential; from begging for help to being the mentor; from rags to riches. My partner, Mihir, who had once ridiculed my inability to do shit, is now on his knees begging for gradients. All of this because of one person, Mr. Lopez.";
    var text2 = "Fortnite Battle Royale is a free-to-play battle royale video game developed and published by Epic Games. It is a companion game to Fortnite: Save the World, a cooperative survival game with construction elements. Create, play, and battle with friends for free in Fortnite. Be the last player standing in Battle Royale and Zero Build, experience a concert or live event, or discover over a million creator made games, including racing, parkour, zombie survival, and more. Each Fortnite island has an individual age rating so you can find the one that's right for you and your friends. Find it all in Fortnite... hop on.";

    setTimeout(function() { typeWriter(text1, 0, 'content1'); }, 20);
    setTimeout(function() { typeWriter(text2, 0, 'content2'); }, 20);
</script>
