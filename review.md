# Review

## Info

Reviewer Name: Jamie Tan

Paper Title: The Protection of Information in Computer Systems

## Summary

_The Protection of Information in Computer Systems_ is a tutorial style, bottom up examination of protection systems necessary to support information protection. Section I introduces and defines many basic security concepts, design princples, protection system schemes, and authentication mechanisms. Section II further details the nuances of capability and access control list based systems. Finally, Section III reviews the state of the art at the time, including existing implementations and research directions.

### Problem and why we care

Protection in computer systems was undervalued, understudied, and under defined when this paper came out (and arguably still are today). By introducing frameworks and design principles defining information protection systems, we encourage better and more carefully crafted protection engineering in the community.

### Gap in current approaches

When this paper was published in 1974, there didn't exist an exhaustive bottom-up explanation of protection systems based on existing system implementations, although a top-down study focusing on the abstract concepts of protection had been published by Lampson.

### Hypothesis, Key Idea, or Main Claim

Certain design principles should guide the structure of a secure protection system. Protection systems are motivated by use cases and are essentially distinguished by how each handles dynamic updates. Mechanisms and architectures should be well matched to user’s image/model of the problem to be solved.

### Method for Proving the Claim

Explain and demonstrate protection mechanisms by explaining the implementation of an example system and progressively adding features to it.

### Method for evaluating

N/A

### Contributions: what we take away

The fundamental security concepts and design principles are still used to discuss security systems today. Additionally, from reading this paper you get an appreication about how deeply use cases influence protection systems, and how simple schemes can be extended for flexibility.

## Pros (3-6 bullets)

* Extremely well organized and structured paper.
* Many use cases to explain and demonstrate protection concepts.
* Ideas defined in this paper are still fundamental today.

## Cons (3-6 bullets)

* The focus of a particular implementation/processor may be limiting what protections we can discuss. (ex. virtual memory)
* List of design principles may not be complete.
* Not as much discussion about authentication mechanisms.

### What is your analysis of the proposed?

I think this is a fantastic and extremely fundamental paper in the world of computer protection. In conjunction with Lambert's paper, the theoretical tools introduced to model, reason about, and design protection mechansims provide an invaluable common language among engineers.

## Details Comments, Observations, Questions


