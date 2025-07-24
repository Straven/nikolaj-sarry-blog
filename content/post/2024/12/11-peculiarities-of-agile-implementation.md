---
title: "11 Peculiarities of Agile Implementation"
date: 2024-12-02T15:43:12+02:00
Description: "After the article on the myths associated with Agile, it would be strange not to discuss: how to understand if the implementation of Agile is done correctly, which framework to use when, who in the company should be responsible for the transition to Agile."
draft: false
Tags: ['agile', 'myth', 'agile-myth', 'agile-implementation']
Categories: ['thoughts-out-loud']
DisableComments: false
series:
    - agile-myths-and-peculiarities
thumbnail: "images/2024/12/11-agile-implementation-features.webp"
toc: true
---

After the article on the [myths associated with Agile](post/2024/12/9-myths-about-agile), it would be strange not to discuss: how to understand if the implementation of Agile is done correctly, which framework to use when, who in the company should be responsible for the transition to Agile.

I have divided the specifics of Agile implementation into two categories: company related and team related.

## How do the specifics of the organisation affect the implementation of Agile?

### Peculiarity #1. Industry preference for agile.

According to surveys, Scrum is the main method used in software development, financial institutions prefer Kanban, and telecommunications companies use both Scrum and Kanban.

In my opinion, this situation is due to the following reasons:
- The pace of change in IT is much faster than in finance. The need for accurate metrics to drive change in finance is greater than in IT. IT companies prefer Scrum because they need fast experimentation, flexible management of priorities, the ability to change the development vector depending on external changes and input data. Finance companies are more conservative.
- The cost of failure is much higher in finance than in IT. That's why they prefer Kanban, which is based on mathematics and statistics, rather than experimentation. Kanban allows for small permanent changes that improve the workflow as a whole.

In telecom companies, both options coexist because they have several development vectors. One of these is digitisation, where there is no clear view of the end result. In addition, software development and hardware infrastructure support are more closely related in telecom than in finance. So, in addition to Scrum experiments, there is a need to accelerate the current processes by applying Kanban.

### Peculiarity #2. Implementing Agile in mobile development.

The main difficulty in mobile application development is defining the requirements for the application. It is difficult to identify stakeholders at the design stage. These difficulties can be overcome by using customer development to conduct customer research and Scrum to analyse product hypotheses.

**Customer development** is an approach to creating a product by constantly testing it in the real market and making changes based on the results of the experiments. This approach is similar to the scientific method, where the process of product creation is scientifically justified. **CustDev** is one of the elements of the Lean Startup methodology, which is one of the agile approaches to product development.

Agile methodologies are generally well suited to mobile development. It ensures: rapid response, involvement and coherence of specialists, rapid delivery of results and rapid changes to them.

In addition to Scrum, there are approaches specifically designed for mobile development. For example, the Mobile-D approach is based on XP, Crystal and RUP - rather old and proven approaches. The main difference between Mobile-D and Scrum is the presence of clear phases and the shift in focus to the engineering side of product development. Mobile-D is more focused on the product manufacturing process, thanks to XP practices, and allows the process to be formalised, which RUP provides.

Another approach to mobile development, [SLeSS](https://www.researchgate.net/publication/266742377_Adopting_an_Agile_Approach_for_the_Development_of_Mobile_Applications?ref=nikolaj-sarry.info), combines Scrum and Lean Six Sigma. In this approach, the workflow is set up according to Scrum and then Lean Six Sigma approaches are plugged in for quality management. SLeSS combines the flexibility of a decision mechanism with statistically based decision making.

However, it is important to remember that the Scrum Guide does not prohibit you from incorporating other approaches into your workflow, as well as tools that may be useful for product development. So you can combine 'classic' Scrum with whatever suits you best.

### Peculiarity #3. Modification for private conditions.

Let's look at Scrum and Kanban separately.

Scrum is a framework, all elements of which are mandatory. None of the elements can be discarded. But there are no strict requirements how and exactly these elements have to be used. Scrum does not forbid to add something if it is necessary for the work and helps to improve the process.

Kanban is a set of metrics and tools. There is no obligation to use them and no rigid requirements to use them. You can use any tools, in any combination, as Kanban is designed for a long process of evolution of an existing system. But Kanban requires regular collection and analysis of workflow data. Without this, you can't measure the success of the application and you can't expect change. But as Edward Deming said, "You don't have to change. Survival is voluntary."

### Peculiarity #4. Tools should be applied with an understanding of their use.

The biggest mistake in implementing any agile methodology is to try to use its tools without looking at how and why exactly they are being used.

For example, when implementing Scrum, they simply rename the Project Manager to Product Owner and the Project Team to Scrum Team and demand results every two weeks. For some reason this doesn't work and the Scrum implementation is scrapped because 'Scrum doesn't work'. But let's understand why this happens:

- Renaming a project manager as a product owner does not give him any authority, i.e. he cannot shape the vision or change the implementation priorities. He or she still has to coordinate with his or her superiors, and is still bound by requirements, deadlines and scope of work. The speed of decision-making does not change. There is no acceleration and adaptation to change.
- The project team does not change after being renamed to a Scrum team. The people are still in the same departments as before the renaming and therefore still report to their line managers, not directly to the Product Owner. As a result, product tasks will have a lower priority than departmental tasks, so the speed of product implementation will not improve in any way.
- In addition, there is no question of the team working on a specific project. Any team member can be involved elsewhere. Even though Scrum clearly states that team members spend 100% of their time working only on the product led by their Product Owner. If people are divided between projects/products, they will switch between them, which drastically reduces the commitment and consequently the effectiveness of the work on each specific project/product.

The negative consequences of such an inappropriate implementation are many. The source is an attempt to reproduce the mechanics but not the essence of Scrum.

### Peculiarity #5. The flexible methodology should be competently implemented in the company.

Given that Scrum is based on teamwork and the priority is speed of product delivery to the customer, 360 surveys are the best way to check the success of the implementation.

They allow you to more reliably measure the maturity of the team and customer satisfaction. After the survey, it is essential to conduct an analysis involving the entire team and stakeholders. This is necessary to show what the team's work looks like from different perspectives and to turn the results of the analysis into concrete actions to improve the work.

## Team related pecularities

### Peculiarity #6. The initiative for implementation should come from the business.

A Scrum implementation always starts with a business objective. Therefore, the first thing to think about is speeding up the process, either externally or internally. It is necessary to develop the product concept in such a way that it can be released iteratively. Then, and only then, can you start building the team. The 'Scrum for Scrum's sake' approach will not work. It will lead to wasting resources on tasks without achieving the desired result.

Who in the company should be responsible for the implementation is a question with no right answer. The initiators of change can be: the technical director, top managers, or the initiative can come from line staff. It all depends on the energy and motivation of the person, on their ability to integrate their vision of the process into the business process of the product or division using flexible approaches.

Ideally, the initiative will come from top management.

### Peculiarity #7. Mandatory and optional roles and functions associated with agile methodology.

In the case of Scrum, for example, these are Scrum Master, Product Owner, Scrum Team. All these roles are mandatory. The development team is also a 'role' because it brings together all the people involved in the process of working on the product: analysts, designers, programmers, testers, etc.

Optionally, the Scrum Master and the Product Owner can have assistants to perform some of their tasks, but the responsibility for the outcome still lies with the Scrum Master and the Product Owner.

**The product owner** is most often, but not necessarily, someone from the business.  If we are building an engineering solution for manufacturing, it might be the chief engineer. If we are building an accounting solution, it might be the chief accountant. In simple terms, this is the person who best understands what and who we are building the product for, what problems we are trying to solve with it, and what priority should be given to tasks during its implementation. It is important that the Product Owner has the necessary authority to independently determine the composition of the product. He should have the right to say "no" to all the stakeholders he interacts with. This is necessary for the coordination of priorities and operational decision making.

**A Scrum Master** is a person whose job it is to create a strong, cohesive, responsible and self-organising team. It is important to realise that this person is neither a team leader nor a supervisor. A Scrum Master does not have the right to give instructions or to interfere directly in product development. He is an organiser, a coach, a facilitator. Project Managers who have undergone appropriate training and have managed to move from a directive communication style to a mentoring one are best suited to the role of Scrum Master.

**The mentoring style of communication** is when communication is on an equal footing. A Scrum Master should not see his interlocutors as subordinates to be supervised, but as independent people. He should push them towards independence and self-organisation. And only when they reach a dead end, does he intervene directly and help with his expert opinion. In other words, the mentoring approach replaces the directive approach with a delegating approach.

***For example**. A subordinate comes to a manager and says, "I can't choose an implementation option. You choose one. If you are using a mentoring approach, you should ask questions such as "Why these options?", "What is the difficulty in choosing?", "What are the strengths and weaknesses of each of these options?" and so on. By asking such questions, the supervisor helps the employee to explore. As a result, the person himself understands how the choice should be made and agrees the timing with the manager.*

Delegation is followed by visioning. With the visioning approach, the team reaches a level of responsibility where the manager only provides high-level task definition from a business perspective. The team independently identifies solution options, estimates timescales and identifies risks. The manager only has to look at it and possibly add something from a specialist point of view and make adjustments if necessary. The parties then agree on the timing of the results. The team is then responsible for implementing and presenting the results. In a visioning approach, the manager acts as a mentor to the team in achieving the business objective.

There may also be an agile consultant. Their role is to set up the workflow, train people to work in it, provide tools for activities within the methodology, including conflict resolution. Ideally, he should do his job in such a way that his involvement is no longer required.

The transition period is always uncomfortable, and the Agile consultant should help the team get through it with minimal friction and develop comfortable and effective ways of working.

When scaling, additional roles may be introduced, but they should still be based on the principles of the Scrum Master or Product Owner, just at their own hierarchical level relative to the product.

### Peculiarity #8. Distinguishing between the roles of product owner and Scrum master.

It is not uncommon for a company implementing Scrum to assign the role of Scrum Master and Product Owner to the same person. This is usually done for reasons of economy. But these are fundamentally different roles with different responsibilities.

The Scrum Master is responsible for the viability and effectiveness of the team, while the Product Owner is responsible for the interests of the business.

For the team to achieve successful results, the system needs to be in balance. If the Product Owner is 'squeezed', the team will be overworked and we will end up with demotivated and unengaged people. If the Scrum Master is 'squeezed', development will go haywire with constant discussions for longer than it should.

In an ideal world, the picture should look like this. So let's imagine that the Scrum Master (SM) and the Product Owner (PO) meet before the start of the next sprint.

***GP**: We have to do a feature like this! We did a great job in the last sprint, so I think we can do it!*

***SM**: In the last sprint, a feature of this complexity required the team to work weekends and overwork during the week. The team worked to the limit. Another sprint like that and burnout, sickness, etc. will set in. We shouldn't let it get to that point.*

***GP**: Is it that bad? Then let's discuss it with the team, we need to determine what we can do in a sprint without overworking. We need to define what we can do in this fiche that doesn't look complicated. It needs to be at least partially implemented in a mandatory way.*

***SM**: Agreed. Only the team can decide that. I will prepare a meeting.*

***GP**: Great.*

### Peculiarity #9. An employee who is going to try on one of the described roles should learn the methodology and the management model.

In terms of business skills, there are no differences from traditional management, except for the prioritisation of stages and closer interaction with the team.

**The Product Owner** should be familiar with Lean Startup, Customer Development and other approaches to product development in order to choose the most appropriate methodology or tools when starting a new product development.

**A Scrum Master** should have a wider range of skills including: facilitation, conflict management, group dynamics, coaching, consulting, agile practices. In general, he does not need technical knowledge, but more psychological skills.

### Peculiarity #10. Collective ownership of the code.

This can be done without agile methods. It is enough to agree on code reviews and other formal rules. Developers can continue to act independently.

Often, companies themselves create 'star' engineers. This is due to the fact that it is more profitable for a company to hire a super-specialist and give him or her a whole area of personal responsibility than to assemble a team of specialists, implement systematic risk mitigation and increase their professionalism.

The question of hiring a 'star' is a choice between short-term and long-term success. At first glance, hiring a star looks like a lifeline for the business. But think about what will happen in three, five, ten years' time. He or she will become indispensable and you will be faced with the following problems:
- Star has no free time. This is partly the fault of the company itself: 'We pay you a high salary, not for leisure'. The result is that you either burn out or become cynical and make the best of the situation.
- There is no leverage on the star. In the long run, such an employee begins to manage the company's priorities. Instead of solving a business problem, they make their own decisions about what to do and what not to do. Over several years of work, he has learned everything about the product and the system, and the worst thing is that he knows more about it than anyone else. Such specialists are not in a hurry and do not want to share their knowledge, they keep it to themselves and use it as insurance or leverage in case of threatened dismissal or salary reduction, and sometimes even for promotion or salary increase.
- You lose scalability. You will not be able to accelerate development if the star is happy with the way things are and will not change. If you recruit newcomers, you will be disappointed and have a high turnover rate, because newcomers will not feel comfortable working in an environment where nobody wants to help them, because 'stars' do not want to share their experience and knowledge, because they do not need competitors.

### Peculiarity #11. Team Approach.

- Accept the risk of losing 'stars'. Not everyone will accept the new approach. This is inevitable.
- Change the structure of attendance. For example, introduce bonuses for writing documentation or training new staff so that it becomes routine.
- Find 'stars' who want to grow and are willing to share their knowledge and experience, and help them learn management, facilitation and coaching skills. Show them new opportunities. Not everyone will agree. But those who do will be good adopters of the new way of working.
- Dilute established teams by taking 'stars' out of their comfort zone. Ensure that there is only 1 'star player' in a team of 4-5 people. You will also need a skilful - Scrum Master who can reassure the old guys that they are in no danger, and at the same time teach the newcomers to be respectful of the more experienced. If possible, it is also desirable to physically move the team from where the 'star' used to sit.

![Implementing Agile](/images/2024/12/implementing-agile.webp)

With the introduction of agile methodology, we are dealing with the transformation of corporate culture, and this is a more complex task. As Peter Drucker said, 'Culture eats strategy for breakfast'. No matter how perfect a strategy you propose, you will not be able to implement it if people do not 'embrace' the appropriate behaviour.
