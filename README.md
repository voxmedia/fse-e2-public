# Vox Media Chorus Full Stack Engineer E2 Exercise

## Intro

During the technical interview, you’ll be asked to work through an engineering exercise.  Over approximately 40 minutes, you’ll be given a problem to solve, including incomplete methods to flesh out.

You will have the choice of approaching the problem in either **Ruby** or **JavaScript**.

### Exercise scenario

*This exercise mimics (in simplified form) some of tasks that we might do day to day, such as understanding and working with JSON data structures.*

You recently migrated several videos from the site **Oldtube (oldtube.com)** to **Newtube (newtube.com)**. As part of the migration, the `id` and `url` of a video on `oldtube.com` is different from the same video on `newtube.com`.

Luckily, each video has a `unique_slug` that is the same across both sites.

For example, the video "Episode 1" on *Oldtube* has the following attributes:

```
title: Episode 1
id: CAW1
url: oldtube.com/1
unique_slug: D473
```

That same video on *Newtube* has:

```
title: Episode 1
id: 2341
url: newtube.com/1
unique_slug: D473
```

As part of the exercise, you will be asked to implement several methods that examine the videos that you migrated.

### Preparation

We ask that to prepare, you:

1. Clone this repo `https://github.com/voxmedia/fse-e2-public` to your computer
2. Choose either JavaScript or Ruby
3. Make sure you can run one of the following in the `fse-e2-public` repo:
   - `ruby exercise.rb`
   - `node exercise.js`
4. Have your editor of choice ready, and be ready to share your screen

## How we interview

### What we're looking for

*We don't believe in “gotcha” coding or technical interviews -- this is an open book, collaborative exercise to let us see how you approach and solve a problem.*

We're **not** judging on how many algorithms or libraries you've memorized, or how much immediate knowledge you have about the esoteric aspects of a language. Use Google, Stack Overflow, libraries, whatever other resources you’d normally use.

We **are** interested in making sure you're able to accurately show us how you approach problems, and how you break down and think through technical scenarios. We want to see how you explain your thought process. Your interviewers won’t be silent observers, but collaborators! We will help you if you get stuck, as that's what teammates would do.

### Live coding

Typing with someone’s virtual eyes over your shoulders can be stressful, so we’re not looking for you to immediately figure out a solution or approach.  Programming can be a process of iteration, and it's how you get there that's useful for us, not when.

You might be nervous coding live, and we understand that you may not be as comfortable as you’d normally would.  That’s okay! We’re not looking for perfection or production quality code.

Besides, our code almost never works the first time around too.
