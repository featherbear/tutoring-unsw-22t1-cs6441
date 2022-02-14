---
title: "Week 1"
layout: "bundle"
outputs: ["Reveal"]
date: 2022-02-14T23:44:17+11:00
---

<style>
    .reveal {
        font-size: 36px;
    }
</style>

{{< slide class="center" >}}

## COMP6441 Week 1

##### Welcome to Security

---

# Who, me?

{{% section %}}

![](./me.jpg)

---

> `andrew.j.wong@unsw.edu.au`  

> Slack - seceduau.slack.com  
> @`featherbear`

> [featherbear.cc/tutoring-unsw/contact](https://featherbear.cc/tutoring-unsw/contact)

{{% /section %}}

---

## Today's Agenda

* Housekeeping stuff
* More housekeeping stuff
* (Lecture review stuff)
* More stuff

---

## Housekeeping

{{% section %}}

### Course Contact

> `cs6441@cse.unsw.edu.au`  

> Slack - seceduau.slack.com  
> `#cs6441`

> [featherbear.cc/tutoring-unsw/contact](https://featherbear.cc/tutoring-unsw/contact)

---

### Resources

> [Open Learning](https://www.openlearning.com/unswcyber/courses/security-engineering-22t1/)

> [featherbear.cc/tutoring-unsw](https://featherbear.cc/tutoring-unsw)

---

### Labs

🍉 Food - Sure

🎥 Recordings - maybe?

🚪 Room Location - SECedu Lab (soon)

🤒 COVID-19 - wear masks, stay home if sick, etc...

> 🙋‍♂️ Ask questions!

<!-- 👩‍🏫 Lab Attendance - Not marked   -->

{{% /section %}}

---

### New number, who dis?

* Name
* Why you decided to pick this course
* Something interesting in your photo gallery / meme collection that describes yourself

<img src="icebreakers.jpg" height=350 />  

---

{{< slide content="secedu.goodfaith" >}}

---

## About The Course

{{% section %}}

> This isn't a hacking course

---

### COMP6441 vs COMP6841

&nbsp;  


* COMP6441 - Broader security
* COMP6841 - More technical

&nbsp;  

> If you want to change, let us know!

---

### Where To?

* [COMP6[84]43](https://www.handbook.unsw.edu.au/undergraduate/courses/2022/COMP6443) - Web Application Security
* [COMP6447](https://www.handbook.unsw.edu.au/undergraduate/courses/2022/COMP6447) - System and Software Security
* [COMP6[84]45](https://www.handbook.unsw.edu.au/undergraduate/courses/2022/COMP6445) - Digital Forensics
* [COMP9447](https://www.handbook.unsw.edu.au/undergraduate/courses/2022/COMP9447) - Security Engineering Workshop
* ...
* a job (that pays well)

&nbsp;  

📝 Some courses have grade pre-requisites

---

### Course Overview

* [OpenLearning](https://www.openlearning.com/unswcyber/courses/security-engineering-22t1/courseinformation/about/)
* Lectures (Buckland Rants™)
* Labs (Case Studies)
* Something Awesome (30%)
* Portfolio / Log Book / Activities (40%)
* Final Exam (30%)
* Lightning Talks (bonus mark)

_Check the course outline for the schedule_

---

### Labs 

* Weekly case studies
* <s>Discussions</s> Talking to real people
* Come prepared!
    * Some are kinda long, some are super short
    * Also sort of marked

---

### Something Awesome

* You pick your own security-related project
    * _(has to be legal)_
* You pick your own marking criteria
* You decide your schedule(ish)
    * Proposal due soon™
    * Project due Week 8
    * Presentations start in Week 9

Ideas: Make something, break something, test something, do a CTF, teach, ???

---

### Portfolio / Log Book

> [Summary](https://www.openlearning.com/unswcyber/courses/security-engineering-22t1/courseinformation/about/?cl=1) of weekly activities

🎯 Create a page in the class group

* Analysis
* Activity breadth
* Activity depth
* Professional Community
* Dealing with challenges

---

### Lightning Talks

> Present a 3 - 10 minute presentation about something security related!  

* Bonus marks!
* Get in touch with me

---

### Class Notes

* Shared notes that will be useful for the finals
* Add notes
* Ask questions
* Answer questions
* Make it look 💅 pretty 💅
* This class (T10A) is on for this week!

> Have a class chat?

---

### // TODO: Class Representative

weeeeeeeeeeeeeeeeeeeee

🤷‍♂️

{{% /section %}}

---

### Things To Do

* Join the T10A OpenLearning group
* Join the #cs6441 Slack channel
* Start thinking about your Something Awesome
* Lecture class notes
* Weekly activities

---

## Lecture Review

Questions?

---

a lil' scenario for this week

> Note

* Incident response
* This is not an ethics course
* I am not a lawyer
* Plot holes everywhere

---

## brrrr[.](https://www.openlearning.com/unswcyber/courses/security-engineering-22t1/casestudies/rumble)

{{% section %}}

---

&nbsp;  
Location: UNSW.

CSE K17, Sydney, Australia, Southern Hemisphere, Earth, uhh.

---

<u>The year is 2024.</u>  
Elections are soon and Ruchard Bickland is currently giving his election speech. <small>* Not to be confused with Richard Buckland</small>

> Promises

✅ All courses to be pass/fail

🚧 Dedicated roads for the 891 (😭)

🌌 For Pluto to be a planet again.  

🌏 Make Tasmania no longer a part of Australia  
(tbh never was)  

---

oh, and COVID-19 is still looming around. <small>wait what</small>  

> COVID-19 RAT tests are affordable,  
> perhaps too affordable ...  

Because of their rather fast results, the government has mandated that every time someone leaves their home, for _any_ sort of reason, they must test themselves - even if multiple times on the same day

---

However, the over-supply and over-use of tests out in public has caused stress on public cleaning services 🚮. The majority of trash collectors have contracted COVID-19 and have to self-isolate, therefore being out of work, and unable to carry out their duties. Bins aren't being emptied as often as they should.. 🧪

> What are some the issues?

> What are the effects on the community?

---

{{< slide transition=fade >}}

You feel a tremor... <u>the ground starts to rumble</u>.

But the councillor (Ruchard Bickland) <small>(again, not related to Richard Buckland)</small> assures you that there's nothing to worry about™. It's just the construction and road works.

> Should you worry?

---

{{< slide transition=fade >}}

You feel a tremor... <u>the ground starts to rumble</u>.

But the councillor (Ruchard Bickland) <small>(again, not related to Richard Buckland)</small> assures you that there's nothing to worry about™. It's just the construction and road works.

On some beach near Coogee, the surfers are bored because the tides are <u>way lower than usual</u>. Ruchard tells them to refill the ocean with the spare bottles of Mount Franklin water.

> Should you worry?

---

{{< slide transition=fade >}}

You feel a tremor... <u>the ground starts to rumble</u>.

But the councillor (Ruchard Bickland) <small>(again, not related to Richard Buckland)</small> assures you that there's nothing to worry about™. It's just the construction and road works.

On some beach near Coogee, the surfers are bored because the tides are <u>way lower than usual</u>. Ruchard tells them to refill the ocean with the spare bottles of Mount Franklin water.

The ocean wind is also <u>rather loud</u> today...

> Should you worry?  

{{% note %}}
Is this a _warning sign_ for anything?

What should we do?

Get somewhere high!
Tell our friends?
{{% /note %}}

---

jk UNSW is on a giant slope, so we're fine!

right...?

<img src="rumble/high_ground.jpg" height=250 />

What could go wrong?

{{% note %}}
    Sure we're safe for now, but what about the aftermath?

    * Bio-hazards?
    * Water damage?
    * Sludge?
    * Water pipes, power lines, infrastructural damage?

    How will that impact every day life?

    * No power
    * Buy bottled water
    * Toilet paper?
{{% /note %}}

---

> Is anyone at fault?

> What should have been done better?

> What does this say about trust?

{{% note %}}
Causality, correlation

Can we trust everything we hear?

Not only think about the immediate consequences of actions, but the effects

{{% /note %}}

{{% /section %}}

---

### Things To Do

* Join the T10A OpenLearning group
* Join the #cs6441 Slack channel
* Start thinking about your Something Awesome
* Lecture class notes
* Weekly activities
