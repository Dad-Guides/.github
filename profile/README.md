# Welcome to Dad Guides!

## Hi there 👋

Inspired by the community at r/daddit I wanted to share some things that I've thrown together to help me be better dad in the modern age. I wanted to share them with you because as I showed them to other dads they thought they were cool.

## Background

I am a busy professional. I'm currently a lawyer and professor, but once upon a time I was a 20-year-old punk, gamer, and software developer. I wrote my first "computer game" when I was in 3rd grade (roughly 1983), it was a text-adventure. I wrote a database in Volkswriter Deluxe for my baseball cards. I grew up on BBS and IRC. My first professional jobs as a developer was working on the very first corporate intranets for Fortune 500 companies.

But I ain't got time for that shit anymore. When I needed (let's be real, "wanted", nobody NEEDS a 50-week curriculum with historical accuracy and physical side quests) something to give structure to my 7 year old and I spending time together? Well ... there's nothing an old systems designer can't over-engineer! 

## Welcome Aboard

Since you're here, I assume you have some of the same approaches to parenting as me (nothing's worth doing if it isn't worth overdoing). Or not. Honestly, this place is for cool people to share cool stuff to help make us all better dads.

## Design Goals

Docker First. I launch everything* through Docker. It makes for an easy-consistent environment. The caveat here, of course, may be that I have resources external to the project that I may or may not host on Docker. For example, I host postgres on Docker, but try to make it so that if you clone the repo and want to change that you don't have to mess around with all of the code to accomplish it. 

Modularity. Not every body the same stack as you. Docker Compose is a nice way to help define that stack.

Self-Contained. Services in the repo should not rely on outside resources. Where it does, there should be explicit and user-defined API access. For example, access to AI services should use a common API such as OpenAI and let the user add their own credentials/access via settings or environment variable definitions.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
