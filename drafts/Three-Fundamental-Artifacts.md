In the [Three Types of Validation][1] post, we remind ourselves to focus on those activities for which we are uniquely qualified, maximizing our contribution. In [PM Recognition and Evaluation][2] I make the case that the fundamental metric used to evaluate product managers should be 'impact.' Since impact is best demonstrated with durable artifacts, this post will cover the most basic things which serve as concrete evidence about work done and value added.

Here are three solid documents PM teams have used to improve communication and demonstrate impact, plus some thoughts on creating stories and epics. This cycle is quarterly, which seems to be a nice balance between giving enough time for the product teams to produce something meaningful, while also getting product to customers fast enough (but not too fast) that they can provide feedback in a way which can impact the roadmap. You may have different cycle times which make better sense for your industry, and that's OK, too.

Let's dive in:
<a name="quarterly-cycle"></a>
![Quarterly Cycle][4]
In my experience, product managers who follow this process can build credibility. Other business functions will be grateful and align to the predictability of these activities. I’m sure there are other routes to success, but this process has proven solid.

> Hot take: One quarter is generally a good chunk of scope for a PRD. A shorter time span may not allow for significant impact (it takes time to build a meaningful outcome) and longer time spans don't ship value fast enough to learn and adapt within a year. I have a personal adage, “You don’t get paid for the projects you start. You get paid when users adopt the projects you ship.” If you ship just once or twice a year, it’s really hard to get that value into the hands of customer and give yourself enough time to learn from their experience, adapt your roadmap based on those learnings, and show that you’ve course-corrected in time for your annual review. Outside of the Web ecosystem, which has great tooling, if you ship often, it can be hard to make sense of the sheer amount of data coming back. For example, when using [cohort analysis][6], if you track 12 or 24 cohorts over the year, it may take considerable discipline to understand which projects the team executed in that span relate to customer retention. People take time to discover features and capabilities; you may blow past them before they have time to discover what's new. If you track four cohorts per year you have a manageable number of events during the year where you can capture the users’ attention and draw their activities to new workflows. At this cadence, you retain sufficient time to analyze their behavior and act on those insights in a coming release.

## One Pager Project Proposal

Audiences: Product team leads, senior management

The [Project Proposal Summary][1pg-template] is an agile way to kick off the process. A one-pager is a proposal to start a project (not a new product!). At the ideation level it covers what a new scope of effort might be, based on previously collected evidence. A lot of organizations skip this step, but I feel that it’s a missed opportunity to gather feedback and possibly fail fast. The content of a one-pager describes the core idea (the what), the justification (what opportunity, why us?), and especially why this is a top priority (why now?). This document can be formal or informal. At first, I used this document to review with my product development lead and director. If they were aware of reasons that my plan isn’t wise, “we can design flux-capacitors, but they’re impossible to fabricate,” or, “your idea for a flux-capacitor is already to focus of another part of the organization,” etc, then I’ve lost nothing but a few lines of analysis in a document, and possibly I’ve learned something. This is much better than coming out with a fully-fleshed out PRD, only to discover it’s not practical, or already solved in some other way.

At other organizations, one-pagers were a built-in part of the formal planning process. Senior management always wants to be included in the planning process, but they don’t want to dive into details. We'd assemble the entire set of project proposals into priority order, and conduct a series of meetings each quarter which showed what the teams were proposing to work on and the remaining scope which wasn't being prioritized right now. This gave senior management confidence that the organization is aligned, and also gives them a chance to have their input early, when we still had time to adapt our plans. Including one-pagers in your formal planning process is a good way to avoid bike-shedding where big egos want to put their stamp on somethin. Without early planning, this usually surfaces at the end of the project when time and tempers are running short.

## Feature Narrative

Audiences: Potential customers, product development leads

This is an optional step, but I find myself often reaching for this tool as a way of doing validation with customers before fully committing the product development team. The Feature Narrative focuses primarily on the customer workflows, and contains little else. The idea is to, with the most clarity possible, explain how the user solves the problem today (regardless if they use our product), and how you imagine we’d change our product to address that problem. An example might be automating the management of TLS certificates. Everyone has a janky process for this, and would welcome a better solution, but they have a host of restrictions on the manner in which this is implemented. By reviewing with potential customers specifically how their lives would be impacted by this project, I simultaneously got feedback on my idea, heard all about what it would take to make it usable in the real world, and perhaps most importantly, I identified who would be anchor customers and who would be late-followers. Skipping this step would have meant I'd have a harder time later, because I'd need to collect compelling evidence and present it at the same time as deep project planning. Doing this work up front made me look better prepared, especially when I had customer feedback already in the books.

## Product Requirements Document

Audiences: Practically everybody!

Plenty has been written about [Product][introverted] [Requirements][atlassian] [Documents][reforge]. When I worked with Agile/XP engineering teams, I abhorred PRDs. As I’ve gained more experience I’ve come to appreciate them, and now _feel that they are the most effective artifact a product manager can produce_. Regardless of the other steps in the process, if a product manager writes an excellent PRD, everything else becomes a lot easier. That’s because the PRD is the one place where a product manager summarizes nearly all of their daily activities. At a high level, it is the master plan of what the team is actually going to do to affect an outcome.

The PRD is a complicated document. If you've taken the time to write a One Pager and a Feature Narrative, you won't have to work as hard, because a lot of the content can be copied and pasted from those previous documents. The remaining work of the PRD will be to connect the workflows from the Feature Narrative to phases, and to define the requirements and acceptance criteria to ensure success.

For a deep-dive into the structure of a Product Requirements Document, review my [PRD template][prd-template] on Google Docs.

The PRD is the final document that happens during each quarterly planning cycle. A critical aspect of the PRD phase is that there must be a mandatory approval step, represented by the red dot in the diagram. I prefer this approval is in writing, rather than during a meeting. The point of the PRD is to drive alignment, so the most durable aspect is that there was a point in time when every stakeholder function agreed on product direction.

The moment the PRD is approved, it starts to decay, because it gets sent to product development team for implementation. As soon as that happens, the Source of Truth is the epics and the stories, because everything starts to change the moment you put pen to paper. You don't have to go back and update the PRD every time the team makes a decision, but it's best to make sure that epics and stories are updated, even if you have to add a story to document the change.

### Requirements and Acceptance Criteria

Since the most important function of a PRD is to drive alignment, the Requirements and Acceptance Criteria are critical to outlining **what** the team will produce to achieve the desired outcome. Sometimes it's hard to tell the difference between a Requirement and an Acceptance Critieria. Here's how I define them, does this make sense to you? Do you have different definitions? I'd love to hear about it.

**Product Requirements**

Product requirements are what the customer is going to evaluate to decide if a product, or some feature of the product, is worth using. *Customer* requirements are the voice of a single customer, and are often very specific, sometimes even discussing an exact implementation. In the [Product Identity][product-identity] article, I cover how we take customer requirements and measure them against the product's direction and the markets we want to address. Customer requirements, at most, show up in the Customer Research section of the document. Try not to pass-through customer requirements to product requirements! Product requirements should be phrased with respect to the potential users outlined in the Personas & Segmentation section of the PRD. Representing each of those personas, what will they expect to work before they'll decide to use the new functionality you're introducing?

Good example: "The user is able to reach 88 mph **so that** they can initiate time travel."<br>
Less good: "Doc Brown needs the DeLorean to travel 88 mph on asphalt."

Good example: "Allow for an alternate power source in case of primary failure **so that** the user can still time travel in an emergency situation."<br>
Less good: "The product must accept a jury-rigged retaining clip so that a cable may be attached to a lightning rod."

**Acceptance Criteria**

How many times have you bought a book or watched a video on how to do something, only to discover that the effort is greater than the reward? I feel that way about amigurumi. Crocheting cute pint-sized creatures seems really neat, but counting stitches is too much mental load for me to bother. I want the outcome of having cute creations, but not at the level of effort required.

Product requirements should be sufficient to lay out what the team is going to build, but they're not sufficient to guarantee success. Product requirements are what the business decision maker (the purchaser, the product selection comittee, etc.) will evaluate when considering your product. Acceptance Criteria represent what the user will actually do. the steps that we will take, before release, to validate that the outcome promised by the product requirements is actually usable. Acceptance criteria are exact steps we will run, in place of the user, to convince ourselves that the workflow meets a customer's expectations.

Providing acceptance criteria in a PRD is a balancing act. Acceptance criteria are mandatory in user stories, and to include 100% of the acceptance criteria at the PRD level would sacrifice agility during the execution phase. For each Product Requirement, supply just a few acceptance critieria to outline the high-level workflow, but don't feel compelled to go to the user story level - that isn't needed at the planning stage. Since that level of detail isn't needed to win approval, it's not a good use of the reader's time to be presented with a wall of acceptance criteria.

The good news is that if you've done the Feature Narrative already, you're already almost done. I like to copy a simple diagram that represents the ideal user flow for each requirement. Breaking the workflows down into simple steps allows your reader to visualize the steps needed to achieve each requirement in isolation. If you have those diagrams, than the acceptance criteria are simply a re-wording of the diagram into English.

Good example: The user enters the car, and is able to trigger ignition **so that** the initialization sequence begins.<br>
Less-good: A door is provided, with door handle inset, with swing-out hinges adjacent to a driver's seat, and a key-enabled ignition is accessible to the operator."

Good example: The user is able to input their desired time and date destination, and accelerate the car to 88mph **so that** they can initiate time travel.<br>
Less-good: Keys and button controls are mounted on the dashboard which are used to key-in time (HH:MM::SS) and date (DD/MM/YY) then lock-in the desired time destionation via a provided button, and then press the accelerator pedal until 88mph is achieved.

**Note:** I like to include a **so that** phrase in each of my requirements and acceptance criteria because I feel that phrase is key to the product manager's responsibility to connect the "what" to the "why." If you want to deep dive on story writing, check out the [Mike Cohn's article on user stories][user-stories].

## Epics and User Stories
If you do the PRD right, then writing the epics and stories should be a mature of copy and paste.

I know all of this process must seem awfully waterfall. In some ways it is, in that you need time to build a strong case (employing a variety of artifacts) to get the support you need to commit product development to a significant project. It’s also agile, however, in that you are doing all the ground to work gather feedback and fail fast. By treating your artifacts as experiments, you are creating the credibility you need in order to build confidence that the team is doing valuable work.

Having done this preparation work, you should find writing epics and stories to be much easier and better organized than before. If you documented your workflows, then you already know how to define Requirements (epics) which will win anchor customers. If you’ve detailed those requirements in a PRD, and broken them down into high-level acceptance criteria, then you have the drafts of each of the stories you’ll need to write. Further, you’ll create less duplication because stories can point to your PRD for full context.

Once you’ve created those initial drafts of epics and stories, however, the PRD will start to age. And that’s OK! Product life is about constantly incorporating feedback, external and internal. Once your team goes from plan to product, all sorts of issues are going to flow in, requiring you to keep an open, flexible mind. You should review changes in the plan with your anchor customers as frequently as possible, understand risk, and work with your team to come up with strategies to stay on track. This is the daily life of a product manager, exploring that tension between customer expectations and what is practical to implement.

I don’t think it’s reasonable to constantly update the PRD with these new insights and changes. I also don’t think it’s reasonable to go through change control every time you need to zig instead of zag, but different companies feel differently. If you work on silicon, and you’re post tape-out, you may be out of luck. If you work in eCommerce, and it’s holiday shutdown, you may need to wait. But usually, you can adapt your Epics and add stories in such a way that reflect what will actually be implemented, and maintain a record which you and the product development team agree on. Until release notes are published this is the most accurate record of what is being built.

## Conclusion

The quarterly cycle starts with the essential basics of product direction and quickly dives down to actionable work. It’s very rare for a product manager to drop into a greenfield project without any existing investment. (Read more on this below) While the activities described in [Your First 100 Days][100-days] are necessary for the PM to establish her credibility, those are built on these core documents.

I hope that this process can be useful to you, and that you find it easy to adapt to your organization’s needs.

One more thing! This process might be the key to scaling your product management team. Doing planning and execution at the same time is a lot of work! That means that even if the product manager partners with peers as much as possible, and works as many hours as possible, the scope of the projects will necessarily be limited. I’ve had very brief periods of time where I’ve been fortunate to be on teams of PMs associated with a single product area. That has allowed us to trade-off, one PM in planning mode, doing research, talking with customers, the other in execution mode, working directly with the team.

[3-validation]:	Three-Types-of-Validation.md "Three Types of Validation"
[pm-recognition]:    PM-Recognition-and-Evaluation.md "PM Recognition and Evaluation"
[100-days]:	Your-First-100-days.md "Your First 100 Days"
[product-identity]: Product-Identity.md
[1pg-template]:    https://docs.google.com/document/d/1erAowV5wUCiUq2j6Dl4wHKUCnVc7ghXQ2qpF9bntvC0/edit?usp=drive_link "1-page Project Proposal Summary Template"
[quarterly-cycle-img]:	https://raw.githubusercontent.com/pm-practices/pm-blog/refs/heads/main/images/pm-quarterly-life.svg "Quarterly Cycle"
[user-stories]: https://www.mountaingoatsoftware.com/agile/user-stories
[cohort-analysis]:  https://en.wikipedia.org/wiki/Cohort_analysis "Cohort analysis (Wikipedia)"
[prd-template]:    https://docs.google.com/document/d/1h4CbU8Ob9E_vPwjyMJVEUVi0RlzUhz5MIdnScJGrL0g/edit?usp=drive_link "Product Requirements Document Template"
[introverted]:  https://introvertedpm.substack.com/p/the-art-of-the-product-requirement
[atlassian]:    https://www.atlassian.com/agile/product-management/requirements
[reforge]:  https://www.reforge.com/blog/evolving-product-requirement-documents
