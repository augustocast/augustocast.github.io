---
layout: post
title: "The 'Meat Proxy': Why Copy-Pasting AI Answers Is Making You a Worse Professional"
author: "Augusto"
date: 2026-08-20 00:52:27 -0300
tags: [ai, coding, learning, llm]
description: "Which tasks are better off not being delegated?"
sticky: true
permalink: /en/2026-08-20-meat-proxy/
translation_url: /2026-08-20/meat-proxy
---


I had a credentials issue with the email account I use for a client project. I filed a support ticket and an AI answered. The reply didn't help me solve the problem, so I escalated the ticket to the agent's *human* supervisor. He answered quickly and, very kindly, suggested a few steps to fix my issue: a copy-paste of what the AI had already told me on the first ticket. I lost two days. Something's off here, and [this](https://gruhn.me/blog/2026-08-03/) post by Niklas Gruhn helped me think it through.

Gruhn's central argument is that answering a question with "the chat said: ..." adds no value. He calls the person who does this a "Meat Proxy" — an extension that just reproduces what the chat says. What's interesting is that this behavior doesn't just fail to add value (since you could go straight to the chat yourself), it's actually worse than the chat, because you can't follow up with more questions.

We all fall into this temptation, and delegating answers to an LLM is always within reach. In many cases it works as an accelerant and a force multiplier for our work, but sometimes it carries hidden costs. What costs does it hide, and why are some tasks better off not delegated?

## Short-term gain, long-term pain
From a developer's point of view, getting a question, asking an LLM for the answer, and replying with copy-paste feels tempting. It seems like [cheating](https://cenital.com/usar-ia-se-siente-como-hacer-trampa/), getting in seconds what should normally take a good while. The hidden costs: wasting a chance to learn, becoming less valuable over time, and becoming replaceable.

You can't know everything (and you can ask the chat what you don't know), but you can learn what you know, what you don't, and who, when and how to ask. In other words, having (good) judgment. A big part of being a good software developer isn't about writing good code, it's about *delivering value with judgment*. And good judgment is earned through experience, by facing hard situations and learning from them. A developer with judgment is worth more than one without it, so outsourcing the very tasks that build judgment looks like a bad investment.

## Desirable difficulty
How is good judgment forged? There are no shortcuts or magic recipes, or at least I don't know any. The industry works a lot like a [medieval workshop](https://smarthistory.org/workshop-northern-europe/).
Put simply, there are:
1. Senior developers, who "know" how to solve problems, because they've already solved many.
2. Junior developers who want to learn how to solve problems, in order to become Senior.

It takes the Junior longer than the Senior to solve problems, and they have less autonomy. In a mentoring process, the Senior guides the Junior to solve the problem — even if it takes them longer than it would the Senior — delegating part of their own tasks and showing them how it's done. If you take the "easy mode" and delegate the ability to filter, prioritize and communicate, you can get tasks done but you won't learn how to solve problems.

This can look like a quick win, but in the long run it's a [bad decision](https://en.wikipedia.org/wiki/Hyperbolic_discounting). Facing costly processes and having to put in [effort](https://en.wikipedia.org/wiki/Desirable_difficulty) is key to the learning process. If you do literally the same thing ChatGPT does, you could be literally replaced by ChatGPT. And, unfortunately, judgment isn't something you learn once and keep forever. It rusts, so you have to exercise it.

## Delegate the execution, not the judgment
Answering a work message has two sides: on one hand, getting the task itself done. On the other, the work you have to do to synthesize, prioritize, and realize that what you're about to say isn't nonsense.

Delegate the execution, but don't delegate the judgment. Looking up the syntax for a `git rebase`? Execution: delegate it. Deciding whether the bug gets fixed now or just documented? Judgment: don't delegate that.
And there's a cost that gets paid today, not in the future: LLMs generate a lot of text, flat and without hierarchy. A message like that is more expensive to read than one that was thought through, prioritized and written by a person. Every time you delegate the synthesis, you're not saving work — you're just passing it on to whoever reads you. And your coworkers notice, even if nobody tells you.

Even if it takes you a bit longer, it's a good idea to think for yourself about the content of your Slack messages, your Jira tickets, or your reports.

Don't let an LLM think for you, or you'll end up being a Meat Proxy: the supervisor who copies and pastes without judgment and costs a developer two days of work.
