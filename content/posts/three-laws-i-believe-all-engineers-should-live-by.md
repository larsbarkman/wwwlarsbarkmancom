---
title: Three Laws I Believe All Engineers Should Live By
date: 2022-09-02
description: 'There are some laws that are more fundamental than others and in this post I describe what I believe are the three most important laws an engineer should live by in their professional life.'
image: images/trent-erwin-UgA3Xvi3SkA-unsplash.webp
---
*Photo by [Trent Erwin](https://unsplash.com/@tjerwin) on [Unsplash](https://unsplash.com)*
  
**There are some laws that are more fundamental than others and in this post I describe what I believe are the three most important laws an engineer should live by in their professional life.**

The three laws are **Gall's law**, **Conway's law** and **Boyd's law**, I will go through them in order and explain my view on them.

# Gall’s law
>A complex system that works is invariably found to have evolved from a simple system that worked. The inverse proposition also appears to be true: A complex system designed from scratch never works and cannot be made to work. You have to start over, beginning with a working simple system.  
> – John Gall (General systemantics, an essay on how systems work, and especially how they fail, 1975)

It's important to remember when reading this that the definition of a system is: ***"A system is a group of interacting or interrelated elements that act according to a set of rules to form a unified whole. A system, surrounded and influenced by its environment, is described by its boundaries, structure and purpose and expressed in its functioning."***. This law (and the two others as well) are therefore equally applicable to digital, analog or human systems. The engineer has the important task of communicating this law to other stakeholders and work towards it being considered as a guiding principle. If the assignment e.g. is to build a new system (think of the broader definition) from the ground up, it is important to get everyone to understand (and accept) that it requires everybody to start with a small and simple system that is proven to work and thereafter add piece by piece, always validating that the system still works as intended (i.e. an iterative process with incremental deliveries). If the assignment is to "fix" an existing complex system that does not work, the stakeholders need understand that it is necessary to start over and work as if it were a new system that was built. In the situation of a complex system that does not work, stakeholders sometimes start talking about how much time and money they have already put into the system. In that case, remind them of the sunk cost theory: ***"A sunk cost is a cost that has already been incurred and cannot be recovered. Sunk costs are contrasted with prospective costs, which are future costs that may be avoided if action is taken."***.

# Conway’s law
> Any organization that designs a system (defined more broadly here than just information systems) will inevitably produce a design whose structure is a copy of the organization's communication structure.  
> – Melvin Conway

Conway's Law has been around for a long time, but it has been absolutely central in the architectural paradigm shift we've seen in the last ten years. What is so important about the law is that it indirectly states that there is no point in trying to change the systems before you have made adequate changes to the organization. If you try to change the systems first you will eventually end up close to where you were before and having to fight the organizational structure along the way. Lucky for us, there is a pattern to address this problem, and it's called the Inverse Conway Maneuver and states: ***"The 'Inverse Conway Maneuver' recommends evolving your team and organizational structure to promote your desired architecture. Ideally your technology architecture will display isomorphism with your business architecture."***.

# Boyd’s law
>Speed of iteration beats quality of iteration.    
> – Colonel John Boyd

To really drive home the importance of an iterative process with incremental deliveries, we can look at the law that Colonel John Boyd formulated after studying dogfights in the 1950s. He was able to state that the primary determinant to winning was not observing, orienting, planning, or acting better. The primary determinant to winning was observing, orienting, planning, and acting **faster**. In other words, how quickly one could iterate. Speed of iteration, Boyd suggested, beats quality of iteration.