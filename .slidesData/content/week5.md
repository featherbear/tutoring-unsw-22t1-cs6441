---
title: "Week 5"
layout: "bundle"
outputs: ["Reveal"]
date: 2022-03-15T00:04:31+11:00
---

{{< slide class="center" >}}

## Week 5

---

## Something Awesome

> You, you're awesome 💖

---

{{< slide class="center" >}}

## Case Study

[👩‍⚖️ Snoop](https://www.openlearning.com/unswcyber/courses/security-engineering-22t1/casestudies/snoop/)

--- 

## Engineering Stuff

---

> Last Week: [RSA](https://featherbear.cc/tutoring-unsw-22t1-cs6441/rsa/tutorial.html)

---

### A good hash

* Deterministic
* One way
* Unique
* Avalanche Effect

> Collisions?

---

### A good cryptographic hash?

* Preimage resistance
    * Given `h(m)`, hard to find `m`
* Second preimage resistance
    * Given `m`, hard to find `m'` where `h(m) = h(m')`
* Collision resistance
    * Hard to find `m` and `m'` where `h(m) = h(m')`

---

### Attacc

{{%section %}}

> Rainbow tables

🌈

---

> Collision attacks

What's wrong with `hash(message + key)`?

---

> Length extension attack

[featherbear.cc/[...]/hashes/](https://featherbear.cc/UNSW-COMP6441/blog/post/hashes/)

More on this next week

{{% /section %}}

---

### Protecc

