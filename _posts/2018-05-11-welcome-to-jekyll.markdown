---
layout: post
title:  "5 things I've got while applying DevOps to Networking"
date:   2018-05-13 08:52:14 +0200
categories: learning devops networking
---


I decided to jump out of my comfort zone as a traditional network engineer three years ago, so now this would be the ideal moment to share some of my experiences, by giving you some pointers in case you find yourself in a similar situation.

I started off as a network engineer/architect with over 10 years of experience, I was the very one who loved going into CLI, debugging protocols, reading RFCs and analyzing complex PCAP traces in a traditional IT enterprise environment (Campus, Data Center, WAN, Internet, etc.), but with few relationship with other IT operational areas such as sysadmin, database and, obviously, developing.

I wouldn't say I was bored then, I enjoyed the challenges which I faced, along with getting involved in various international activities close to the industry I was working on (TV Broadcasting). However, whilst following the networking community online, I started to become aware of the fact that the Internet-scale and the dynamic infrastructure/Cloud were bringing new challenges to my area and I didn't feel comfortable with the skills needed in solving them.

So, I decided it was time to move. Move to a place where I was able to contribute with my knowledge & experience and most importantly, learn everything I would need to know for the years to come. I joined [Schibsted[(http://www.schibsted.com/) in 2016, firstly working on corporate network projects, whilst keeping a sharp eye on the actual challenges Schibsted was facing as a global Internet player.

Little by little, I gradually got involved in the DevOps culture, being part of small transversal teams with complementary skills, who focused on building services (internal and external), delivering and evolving them (You build it, you run it!). Fortunately, I had the opportunity to get involved in building a network service from scratch to abstract and automate how developers deal with network infrastructure. 

Describing how much I've learnt in this process is by no means easy for me... It has been challenging at times, I've had to invest a lot of my personal time in reaching the same standard as that of my coworkers, taking in their advices and getting to the point of actually being able to contribute from my own point of view. Apart from delivering the service to production (since Jan 18) other outputs of these works are two talks I delivered on this service, one for a networking audience in [Netnod](https://www.youtube.com/watch?v=TMKG8dww9Fc) and another one for a DevOps audience at [DevOpsBarcelona](https://chadell.github.io/slides/180410_devopsbarcelona/) (The better the second time, just like everything in the real world), where I shared my experiences through all this process. Please, in case you attended to or watched the presentation afterwards, drop me any comment you could have (both positive and negative are welcome).

After having worked on these presentations, I can enumerate some key takeaways for networking engineers who are willing to transform to the new IT era, which are the following:

1) **Don’t be afraid of leaving your comfort zone 💪🏻**. It's easy to say but harder to do. This is not about tech, this applies mostly to the personal experience of learning new things and becoming wiser and, more importantly, building confidence about capacity to becoming what you want. My advice here is to define a mid-term plan on where you want to be in 2 years and, from that strategy, define short-term goals (say, 3 months), also know as [personal OKRs](https://medium.com/@cwodtke/personal-okrs-three-years-later-7616e60574a4). This will enable you to achieve periodical goals and teach you how to adapt in tactical changes depending on your short-term needs.

2) **Learning coding will give you superpowers 🙇🏻**. Even if you usually use off-the-shelf automation tooling, at some point gluing pieces and basic coding knowledge (and data structures) will be needed. There are several languages, but I would recommend trying out Python and Go. Python because it's quite popular in the networking community (do you wonder which language Ansible, Salt and StackStorm leverage on for extensibility?) and Go because for its easy paralleled execution. A good starting point, would be to work on practical use-cases, so the potential benefits of using code (first just scripts) applied to networking can be seen. Useful resources here are [free online course by Kirk Byers](https://pynet.twb-tech.com/class-pyauto.html), the book [Understanding Network Hacks](http://www.springer.com/la/book/9783662444368) or online coding challenge webs such as [Codewars](https://www.codewars.com/).

3) **Adopting a DevOps approach will speed up your business (and career) 🚀**. Trust me, the DevOps culture means moving everyone in one direction, sharing goals and spreading knowledge. So, realizing what you can do in your own area leveraging good practices from software development will transform you into a T-shirt guy as you will become a key player on your team and a valuable candidate for the industry. Recommendable networking focused automation books, such as [Network Programmability and Automation](http://shop.oreilly.com/product/0636920042082.do), could be a good starting point on this area. Disclaimer: if you don't want to get several job offers per week, avoid using the DevOps word from your profile, it's a kind of spam 🤦‍♀️.

4) **There is a community out there, so join it! 👥**. You are not alone, a lot of people from pure networking have made this jump or are taking the first steps in this directions. I would also recommend [NetworkToCode slack community](http://slack.networktocode.com/) to you where several slack channels for every open source project you may know. I remember joining two years ago, when there were around 100 network guys, and today it has more than 5000 members!! And always willing to help. For readers close to Barcelona, I would also recommend the super cool Meetup about [SDN and Network Programmability[(https://www.meetup.com/es-ES/SDN-and-Network-Programmability-Meetup-in-Barcelona/).

5) **Networking is a key skill in IT, bring it close to the business 😎**. Yes, it is. A relevant part of your application user's experience will be affected by how your network performs (latency, throughput, packet loss), so bear this in mind, you just have to make it an enabler and make it worthy for your business.

![](https://docs.google.com/drawings/d/e/2PACX-1vQFUkYeKAIZQLiCoPZ1AgPFKgtsjE_U7wipI5dbHvJYXqn3Ef2pL_ggfiUU3gu0QKpHU4MZTqdzsNjr/pub?w=350&h=360)

Congrats, you have reached the end of this long post, but hopefully some of my ideas have helped you on your personal journey. As an extra, I am going to share my [learning]({{ site.baseurl }}{% post_url /refs %}) list with you, where I've been tracking the most relevant blogs, articles, courses, etc. I've used (or I'm planning to) regarding networking, coding, cloud, linux and culture topics.

I wouldn't end this retrospective without naming just a short list of people who have helped me on my personal journey (with a lot of patience). Thanks to Daniel Giribet, Marc Morata, Daniel Beneyto, Daniel Caballero, Jaume Pinyol, Roger Sole, Valentin Gutierrez, Ulises Olivenza, Adam Stevko, Paco Orozco, and Diego Pomares (in chronological order), amongst many others that I can not mentioning here as the list goes on and on.

Extra point: Similarly to the [DevOps course](https://www.salleurl.edu/en/education/devops-management-course) I'm contributing to, I'm also considering to create & run a 2-3 days "Network Automation & Programmability" **bootcamp in Barcelona** after Summer, so if you are interested in participating (attending or contributing) in, promoting or hosting it, don't hesitate to reach me out, and I would take your points into account when defining it.

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
