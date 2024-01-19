---
title: Beyond the infallible AI
date: 2024-01-19
---

Do you constantly switch between keyboard inputs while typing? As a non-English native, I often communicate using a Lithuanian keyboard layout, but write code using a US keyboard layout. Here is my problem: To utilize the most of my screen space, I have a menu bar in my Mac OS hidden, so I never know which input source is currently selected. This results in typing Lithuanian symbols when I want to type numbers, and vice versa, which I have to delete and retype text again. Happens daily! Yet I have not heard of anyone complaining about it, let alone trying to address it.

So here is what I came up with: Make a tiny dot at the top right corner of the screen whose color would be a non-obtrusive visual indicator of the current input source without claiming any screen space. Super clever!

Since we already live in the future, I implemented this indicator using a combination of ChatGPT, Bard, and Phind ([find the final code here](https://gist.github.com/qbilius/5e6496fd00e6f12a8637e712ec969a11)). Neither tool alone could solve the problem, but more importantly, I did not know exactly how I wanted to solve it either. It was through this dialogue that I gradually came to the final design of the app, and managed to force these tools to tell me how to implement it in Objective-C that I have never used before.

This intermediary between a human and a machine is providing a helpful layer of abstraction where we no longer need to know low-level specifics (different programing languages in this case) to interface successfully. I have been craving for such tools ever since conceptualizing “humanui” in 2018 (an unfunded proposal to create an AI layer to help people use computers; [adept.ai](https://adept.ai) is a good example of what I failed to kickstart) and feel amazed that these tools were developed so rapidly!

But the expectation should not be that these AI assistants are infallible experts. Rather, these are complicated beings – just like every one of us – and it takes effort to find ways into their hearts to make them talk. I took me a whole day to get the answers I needed to write this tiny indicator app. So what.
