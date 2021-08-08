---
title: "The Art of Maximising Work Not Done"
excerpt: "Agile Manifesto Series - Product Owner Reflections"
header:
  teaser: /images/do_it.jpg
  image: /images/do_it.jpg
date: 2021-08-08
tags: ["analysis","productivity"]
categories: [Work]
---

In this post I will share some reflections on the meaning of [Agile Manifesto](http://agilemanifesto.org/principles.html) principle 10, and some practical considerations for Product Owners.

> **Agile Manifesto Principle 10:**<br>
> Simplicity: the art of maximizing the amount of work not done is essential.

## Interpreting the Principle

Listed below are several interpretations of work that might not be done and why they might be considered essential:

- Work not done in elaboration, analysis and design
    - _Ensure that effort to elaborate solutions focuses only on the products and features that will be built next - essential due to the uncertainty involved in predicting the medium and long-term future_
- Work not done in development, testing and deployment
    - _Ensure all software that is built meets a genuine client need - essential to providing a service_
- Work not done in maintenance, operations and support
    - _Ensure software is built to be simple, easy to maintain and easy to use - minimising lifecycle costs - essential to remain competitive_

## The Role of the Product Owner in _Maximising Work not Done_

The Product Owner has an integral part to play in maximising work not done. The Scaled Agile Framework describes the role of the Product Owner as:

> _The Product Owner (PO) is a member of the Agile Team responsible for defining Stories and **prioritizing** the Team Backlog **to streamline** the execution of program **priorities** while maintaining the conceptual and technical integrity of the Features or components for the team." [© Scaled Agile, Inc.](https://www.scaledagileframework.com/product-owner/)_

It is more succinctly described in [this video]({% post_url 2020-03-16-Product Ownership Video %}) as _"Build the right thing"_. Unpacking this definition and linking it to the interpretations of principle 10, I propose, that maximising work not done _is_ the role of the product owner:

- Streamlining program priorities - serves to avoid unnecessary elaboration, analysis and design through aligning clients expectations through tools such as Product Roadmaps <i class="fas fa-check-circle" style="color :green; "></i>
- Prioritisation of the backlog  - serves to avoid unnecessary development, testing and deployment through enabling the team to focus on high value items in serial until the customer receives working software <i class="fas fa-check-circle" style="color :green; "></i>
- Maintenance of conceptual and technical integrity of the features or components - serves to avoid unnecessary maintenance operations and support through a focus how solutions will work within the wider eco-system <i class="fas fa-check-circle" style="color :green; "></i>

## Why is this an _art_?

> Pablo Picasso - "Art is the elimination of the unnecessary"

In software delivery the product owner 'eliminates the unnecessary' through **prioritisation** of the product backlog. Prioritisation requires judgments about the future and is therefore subjective. To make such judgments effectively the product owner must develop a deep understanding of business needs, technical constraints and architecture goals. This deep understanding enables the product owner to set out a prioritised backlog incorporating multiple stakeholder perspectives. This, however, is the easy part. Getting multiple stakeholders to 'buy-in' to the product backlog requires artistry. The product owner must create and sell a clear vision to bring all stakeholders 'on-board'. This 'vision' creation requires an empathetic approach, considering the agendas of the stakeholders and the inherent trade-offs the plan asks them to make. It will likely require the ability to use a range of 'mediums' to convey the vision recognising the communication preferences of the individuals or teams involved. Creating a clear vision, which achieves organisational outcomes whilst managing constraints and personalities is an _art_, stripping away the unnecessary takes both technical understanding and skill and when done well creates space for development teams to deliver excellent products.

## Why is this _essential_?

Building great software takes time. It requires a thorough comprehension of the value proposition / business problem, detailed technical knowledge, the co-ordination and alignment of multiple stakeholders and the management of scarce resources. Wasting time working on software that won't be used or is not wanted is a _'double waste'_. Not only are you not working towards the outcomes that your client or team desire, you are also taking time and energy away from those outcomes. Working on multiple 'priorities' concurrently can incentivise teams to take shortcuts which can prove extremely costly for the product over its complete lifecycle. Berliner and Brimson (1988)[^1] found that 90% of a products lifecycle costs are determined by decisions made in product design ([This Kaplan Article](https://kfknowledgebank.kaplan.co.uk/management-accounting/costing/lifecycle-costing) provides a good summary). Whilst this research was conducted in a manufacturing environment, I propose that the impact of poor design decisions early in the life of a software product is at least as costly, if not more, as support and maintenance costs for poorly designed products can be substantial. Therefore, it is _essential_ to create the time to think carefully about how to develop a product, to ensure that the products that do get to market meet a genuine client need and are straightforward to support.

## Practical Considerations for Product Owners

The PO plays a crucial role in aiding the organisation in determining _what_ gets delivered. It is important that POs create time for clarity of thought and focused assessment of their problem domain and the available options. Creating this time will enable well thought through propositions and tactful approaches to stakeholders increasing the likelihood of delivering elegant and impactful solutions. Questions to ask during backlog elaboration and product design:

- What are the lifecycle cost implications for this proposal? 
- How will we test, modify and maintain this feature?
- Does this proposal create or reduce technical debt?
- Will we still need this in a year?
- How will this be supported?
- What alternative options are available?
- What problem are we trying to solve?

Enquiring questions can help POs to get to the crux of an issue and help expose any inherent trade-offs to key decision makers in the organisation. If a particular endeavour cannot stand up to rigorous scrutiny it should not be progressed! The trick is finding the time to be rigorous.

### Finding the Time to be Rigorous - Applying the Principle to Yourself

It is easy to get caught up in the myriad of activities required daily to deliver software products,and as a result feel very productive, whilst simultaneously failing to take time to properly think about the problem domain, the suitability of the solutions being considered and the lifecycle implications of decisions. In such circumstances the feeling of productivity is unfounded. Failing to think problems through will almost certainly lead to emergent issues in the future that could have been considered earlier in the product lifecycle.

Maximising work not done implies that work that _is_ done receives full and focused attention. This means creating space for creative and innovative thought in your daily activities. This could also mean taking regular breaks or cancelling meetings to focus on a particular challenge. During your working day how often do you critically assess the importance of each task, where it is leading, what alternative approaches could be taken?

Some tips to help maximise work not done:

- Declining Meetings to which you will not add anything
  - _Ensuring that this is done sensitively, with clear communication to the meeting organiser is important_
- Turning off your instant chat
  - _Ensuring that you won't be distracted for a period of time, giving space to think_
- Asking _"why am I doing this?"_ or explaining your approach to a colleague
  - _Ensuring that what you are doing can be linked to the business value or organisational goal_
- Asking _"who else could do this?"_
  - _Ensuring that the right people are involved in problem solving. Sometimes POs can overstep their role in a bid to deliver_
- Push back on requests that require concurrent deliveries across multiple topics
  - _Ensuring that each topic is worked on in serial creates more space for thought_
- If this was my money, would I invest in this?
  - _Ensuring that client value is at the heart of delivery_

By asking such questions POs can start to act like true _**owners**_, taking responsibility to ensure that money invested in the Product is spent wisely and that proper focus is given to maximise the chances of a positive outcome for the organisation and it's clients.

Remember every action you take commits you to a series of follow ups. How will you maximise work not done?


![DOIT]({{ page.header.teaser }})
_Image created by Marak Uliasz - [Licence](https://creativecommons.org/licenses/by/2.0/), [Source](https://www.flickr.com/photos/59632563@N04/6261230701)_

[^1]: Berliner, C. and Brimson, J.A. eds., 1988. _Cost management for today's advanced manufacturing: The CAM-I conceptual design._ Harvard Business Review Press.
