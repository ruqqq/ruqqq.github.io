---
title: "Why I (a software developer) switched over to Surface Go 2 from an iPad Pro"
date: 2020-09-13T12:11:00+08:00
draft: false
---
## Square peg into a round hole

I bought an iPad Pro 10.5" some years back with the intention of making it my ***companion*** computing device. It has powerful processor, lightweight, good battery life and a great screen. Not forgetting, good enough selection of apps too. But somehow, it still ended up being underutilised.

At first I thought the issue was that I needed a keyboard with it to be more productive. So, I bought a Logitech keyboard case. With *Blink Shell* and my knowledge of *Vim*, I did see an increase in productivity. I could *ssh* into my dev machine and get some work done. Not ideal, but it works.

However, soon after, I felt that wasn't enough. I was bothered by not being able to use my expensive iPad to accomplish simple stuffs, like make an edit to this blog. It wasn't impossible, but I have to jump through the hoops to do that. It didn't help that the case adds quite a hefty weight, making the iPad no longer very portable.

I got tired of trying to fit a square peg into a round hole. The iPad isn't simply made for productivity (unless it's art related). It's more of a content consumption device. I guess that's the definition of a tablet nowadays.

## Story refinement

I had own a Surface Pro 3 back during my university days. It served me well. Using a Windows 10 2-in-1 device wasn't a new experience for me. While SP3 was pretty powerful, it can run quite hot given that it runs the usual laptop processor with fan based cooling. It also weigh almost as much as a Macbook Air with the keyboard cover case. Naturally, it does not appeal as a tablet. Its market falls under the lightweight portable computer category.

Today, Microsoft is already at SP7. Unfortunately, the above mentioned caveats still applies and hence does not fit my use case. Then there's SPX, the new kid on the block: runs ARM processor, super expensive, and quite large at 13". There's also this big disclaimer that it is Windows device which can't run any 64-bit Windows apps.

It was pretty clear that my dream device is not in the market yet. I knew had to shave off some less important requirements and lower down my expectations. I ended up with this simple use case scenario: *A device which allows me to get some simple programming work done **AND** also as a content consumption device during commute*.

With this story, it was pretty clear that these are the requirements (priority decreases as number increases):

1. Lightweight (500g~) with keyboard
2. Can run VS Code
3. Fan-less design: does not run too hot so that it can be held in hands comfortably
4. Decent battery life
5. LTE connectivity
6. Has content apps: Netflix, Prime Video

## Surface Go 2

I had overlooked Surface Go during my search due to the bad reviews in terms of performance and the ugly bezels surrounding the screen. However, to my surprise, the Go 2 was just released few months prior. It fixes most of the problems and came with a higher spec m3 processor. Given that it is the only device that fits my list of requirements, after checking various reviews on YouTube, I went for it.

Quick specs of the model/variant I went with:

- 10.5" screen
- 8th Gen Core m3 (dual core with HT) with LTE
- 8GB RAM
- 128GB SSD
- Go 2 Weight: 553g, Type Cover Weight: 245g

## What can it do?

I was pleasantly surprise with this cute little device. Naturally, I deactivated Windows 10S and moved to Windows 10 Home immediately. On the productivity side, it runs VS Code, WSL2, Docker. For heavier workloads, VS Code Remote extension paired with the LTE connectivity comes to the rescue.

On the content consumption side, I have Netflix, Prime Video, Plex and... Edge Chromium. Let me say it a little louder for the people at the back of the room: **Edge Chromium**. A full fledged browser on a very portable device? Yes please. YouTube and few other social media apps basically exists as an Edge Chromium PWA on my Go 2. I no longer have to keep in mind: "*Oh I am on tablet, although not many, some sites just does not work as expected*".

My principle in installing softwares on the Go 2 is simple:

1. Does it have a Windows 10 UWP app and is fully functional? Go for it.
2. Does it have a working website and is fully functional? Go for it.
3. Does it have a desktop Windows 10 app? Okay, no choice, but let's not let it run in the background.

There are tweaks and tips involved to ensure the Go 2 battery life does not suck. I will cover that in a future post detailing my apps and Windows setup

## My hopes for Windows 10 and Go 3

While I am pretty happy with my purchase, Go 2 is far from perfect both hardware and software.

### Battery Life

As expected of a Windows device, the battery life cannot match an actual tablet like the iPad or Samsung Tab. Even with the optimisations I have done, it does use up more battery even when doing basic tasks like web browsing. I went in expecting that so it didn't hurt me as much. It is a trade off for having a full fledged browser. Though, I do hope Go 3 comes with a more efficient processor and bigger battery life.

### Apps

It's no surprise that Microsoft is losing on the apps front. UWP app is the way to go on this device given that it is designed to run efficiently. But Microsoft seemed to have failed to push the adoption to developers. This is evident by MS current move of allowing normal desktop only apps on the Microsoft Store now. Being a Go 2 user now, I am rooting for MS to be able to win on UWP front given that Windows 10X is coming.

### Windows

Windows is very rough around the edges when it comes to touch screen interactions. Everywhere in the OS, you can feel that it is primarily designed for mouse + keyboard interaction. Touch interactions are always an afterthought. While this has improved since the time I have used SP3, it is light years away from Android or iPadOS. Microsoft, I do hope Windows 10X fixes this or Surface Neo will flop.

### Type cover

Best keyboard on a tablet, hands down. I actually felt like I am typing on a real keyboard. The tactility, the key travel, the layout, the trackpad. The main issue for Go type cover is flexing the keyboard causes the mouse button to be clicked. No idea how they got past the QA. The second thing is the weight. Go 2 itself weighs 553g, which is very light. But add the keyboard? Comes close to a total weight of 800g. Still not heavy, but yeah, could be lighter if possible.

## Closing

Having this much (productivity) power on a device which fits in my small sling bag is awesome! I now use the device more often than my iPad. Don't get me wrong, the iPad is a great device. It is just not focused on productivity, or at least, still has a long way to go for that. It is however an extremely potent content consumption device, especially games.

If you're a software developer like me, and need a secondary device to bring along with you anywhere, forget the iPad and trying to workaround its weaknesses. At least for now, Go 2 is the device for you. Windows with WSL2 is pretty comfortable to use. Give it a try!

I hope to write more on my experience with Go 2 as a developer in time to come. Till then!
