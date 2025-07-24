---
title: "12 Killers of Developer Productivity"
date: 2024-12-04T00:48:38+02:00
Description: "One of the most important and popular issues for project managers and technical leaders is increasing developer productivity. Many articles have been written on the subject. Let's take a look at the root of the problem."
draft: false
Tags: ['developer', 'productivity', 'team-management']
Categories: ['productivity']
DisableComments: false
thumbnail: "images/2024/12/12-productivity-killers.webp"
toc: true
---

One of the most important and popular issues for project managers and technical leaders is increasing developer productivity. Many articles have been written on the subject. Let's take a look at the root of the problem.

Almost 30 years after Tom DeMarco and Timothy Lister's book 'The Human Factor' was published, projects continue to suffer from huge productivity losses. And there are many reasons for this misery.

## Breaks and meetings

Interruptions are a major killer of developer productivity. It can take up to half an hour to pick up where you left off. The more interruptions, the harder it is to get back to work. Bottom line - more bugs and errors.

Meetings are the same interruption, and worse. A developer cannot concentrate properly on a task if he knows that the process will be interrupted in an hour or two. Nor can he start a serious task knowing for sure that he will not have time to finish it.

>One meeting, can derail an entire day by breaking it into two parts, each too small, for a complex task.
>
>[*Paul Graham*](http://www.paulgraham.com/makersschedule.html)

Short planning sessions at the start of the day or before lunch can help avoid unnecessary interruptions.

## Micromanagement

Micromanagers are the worst kind of manager in terms of their impact on developer productivity. They create lots of meetings and unplanned interruptions, but that's not the worst of it. They don't trust you, undermine your skills and kill your motivation to work. Very often it is micromanagement that becomes a reason for developers to quit or request a change of team.

## Uncertainty

Uncertainty comes in many forms. For example, incomprehensible bug reports such as 'everything is broken', 'fix it'. The information in such reports is not enough for developers to start working and they have to spend time analysing the situation. Having templates of bug reports helps to resolve such situations.

Uncertainties may exist in the specifications of a new feature. In this case, developers start implementing what they think is right, only to be told by the manager that something completely different was planned and that everything needs to be done from scratch.

Uncertainty also includes fuzzy priorities. Burning tasks can only be done first if the developer knows about them. Otherwise they might do something else. And frustration is inevitable.

## Seagull management

Everyone has probably heard of seagull management. This is an approach where a manager is not involved in the programmers' work at all. He just flies up to the programmers from time to time and criticises everything he sees. Then he disappears, leaving behind an angry and upset developer who will not be able to get back into the rhythm of work for a long time. Unfortunately, this type of manager is even more common today than the micromanager.

## Attribution

When someone else takes all the credit and praise for the work of others, it is a hurtful and very stressful moment. It kills team productivity and motivation for a long time.

## Environment

This includes factors such as: noise, movement, room layout and workstation.

It is extremely important for programmers to work in a comfortable environment. For example, some people prefer white noise in the background - the sound of a computer running, the hum of traffic outside the window, music, etc., while others prefer to work in complete silence.

The constant bustle of colleagues can make it very difficult to concentrate on your work, and if your computer screen is visible to others, it can be a serious distraction. An uncomfortable environment is a major cause of low productivity.

## Project Sprawl

This is the result of uncontrolled changes to the project. It occurs when the original goals are not properly defined, the documentation is incorrect, or there is a lack of proper control.

Simple tasks become complex, the development process is delayed and productivity drops.

Here's a simple example of project sprawl, using the location feature as an example:
- It all starts with the initial requirement definition in the form of 'Show location on map'.
- As the task is nearing completion, the specification 'Show location on 3D map' arrives.
- You complete that, too, but now you need 'Show location on a 3D map that the user can walk around'.

## The Product Definition Process

How does product definition affect developer productivity?

If the team works without showing interest in functionality, it may turn out that a number of implemented features are simply not used. As a result, developers will feel that their work is being wasted and will lose motivation to work on the project.

We all like to feel needed and useful, but for programmers this is extremely important.

## Ignoring technical debt

Technical debt is a deliberate and conscious decision to implement things in such a simple way as to get the product to market as quickly as possible. Sometimes it's unavoidable and helps speed up software development in the short term. However, technical debt complicates the system and slows down developers if it is not addressed in a timely manner.

If you keep moving forward without refactoring code as one of your main priorities, you will have big problems with product performance and quality.

## Tools and devices

Programmers use many different tools to automate their routines. If their working environment is outdated and unable to cope with their tasks, it will complicate the process and reduce productivity.

In addition, programmers are more comfortable working with a large monitor and a powerful computer than with a small monitor and a constantly slow computer.

## Lack of clear documentation of the code

When we first start learning to code, we always come across the thesis about the importance of code commenting. But many programmers misunderstand this thesis and comment almost every line of code. Let's look at a code example from Jeff Atwood's article 'Coding without comments':

```
r = n / 2; //установить значение r равное n деленного на 2

// цикл пока r - (n/r) больше чем t

while (abs(r - (n/r)) > t) {
    r = 0.5 * (r + (n/r)); // установить значение r равное половине r + (n/r)
}
```

Do you understand what this code is for? How it can be used? Where? Probably not. Although there are more than enough comments in this code. The problem is that they tell you what is happening, but do not answer the question 'why is it being done? More or less experienced programmers have an excellent understanding of how assignments, cycles, arithmetic operations work, but it is impossible to guess what data is being processed and for what purpose without additional information from outside. Errors that occur in such code are quite difficult to fix.

## Impossible deadlines

This point is related to the bad habit of managers asking developers for estimates of the time it will take to do the work, and then getting them to lower them so that they can turn these estimates into hard deadlines. Managers love deadlines, see them where they don't exist, and genuinely believe that the fault for missing them lies with the developers, since they are the ones who set them.

Not surprisingly, programmers don't like this approach, as it creates unnecessary tension and prevents them from concentrating on their work.

## Conclusion

![Developer VS Productivity Killers](/images/2024/12/dev-vs-productivity-killers.webp)

The resulting list of productivity killers is not unique to software development. It can be applied to any field of activity. However, programmers require deep concentration and each of these factors can easily undermine their productivity. Technologies have come a long way, but the human factor cannot be ignored. The more comfortable a programmer is, the more efficient he or she will be.
