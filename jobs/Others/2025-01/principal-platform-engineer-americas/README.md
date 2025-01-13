# [Principal Platform Engineer - Americas](https://www.remotewlb.com/apply/principal-platform-engineer-americas)  
### Ashby  
####  

We’re looking for a curious, rigorous, problem-hungry platform engineer (who codes!) to carry the ball as we bring Ashby to the big leagues. Ashby builds software that lets talent teams build an efficient, delightful, respectful hiring process. Similarly, you’re an engineer who wants to build a “paved road” that excellent engineering teams can safely take to the moon and back.

We’ve listed this role twice: as a Platform Engineer and Site Reliability Engineer – our team does both, and we are open to candidates who lean towards one or the other.

# About the role and how we work

I’m Elénie, a Director of Engineering at Ashby. I’ve been an SRE for a long time, but I didn’t begin there. I started my career building algorithms to process large 3D models for civil engineers and route packets faster for telecommunications (“real infrastructure”). There, I found that what makes or breaks the customer experience is the result of often unseen but critical infrastructure work. This critical work makes the admin UI on the website load fast at the airport, the drafts of your models recoverable if your laptop crashes, the data you dearly value, safe.

That’s why I switched from working on product to infrastructure: we’ve all seen those outages first reported by a customer because there’s no monitoring, those cute sadface graphics so you’ll be less angry at the software when it inevitably crashes, those late nights your coworkers spend toiling away at failed releases, missing database rows, or misbehaving firewalls. I wanted to create fully-automated solutions to those reliability issues, and use software instead of processes to make infrastructure updates, inter-team schema changes, or data access safe. This can work very well: the systems I built reduced yearly downtime to minutes, and some were even fun. I believe training people starts with meeting them where they are, and infrastructure engineers have empathy as a core skill.

As a Platform Engineer at Ashby, you’ll do that and more. Every Product Engineer owns their projects and ships with minimal oversight. We, as SREs, approach this from a practical view. We don’t put roadblocks to ensure security when common sense will do and we don’t build processes like change management boards around the lowest common denominator. But with great power comes great responsibility: we handle personal and confidential data about some of the biggest decisions we ever make at work. As we grow, more and bigger customers rely on us to be reliable and secure and how we operate internally will need to evolve.

We’re at an inflection point where our ability to scale and deliver a seamless experience has a make-or-break impact – we have some of the fastest growing companies using our platform every day to hire hundreds of people per month. We need someone like you to make good decisions, debug thorny issues, and build us a future-proof platform that can withstand this scale. Our small but mighty infrastructure team has set up a secure and simple environment (we don’t believe in spinning up a new service unless necessary!) for our growing product team to build in. That’s where you come in: you, too, will own projects end-to-end and have an impact on core parts of the Ashby developer and user experience. For instance, you could work on:

  * Optimize our homegrown ultra-dynamic recruiting DSL-to-SQL compiler, and create tools to help developers do so

  * Create automated guardrails for the security and privacy of our customer data

  * Help our developers ship features fast through canary deploys, gradual rollouts and feature flags, while keeping complexity manageable and reducing downtime

  * Work with the business and the engineering team to define SLOs and implement the corresponding SLIs.

  * Ensure all communication with external services supports retries and circuit-breakers.

  * Implement the infrastructure to support an event-driven architecture and data warehouse.

We’re looking for someone who can build systems that an engineer would like to work with: mature and boring but open-minded and approachable. We have to balance reliability with flexibility. Software and its availability are now mission critical to almost every working professional. To be in an SRE in today’s world, you have to be extremely comfortable evaluating risk, those you take and those others take.

# Why you should or shouldn’t apply

You should apply if:

  * You never stop. You get weirdly obsessed about a problem that doesn’t yet make sense, turn it every which way in your head until the explanation dawns. You’ll search every rock, inventory every clue, hunt every mismatch. We do that, too - together we’ll be armed with state-of-the-art monitoring tools and an impressive amount of data, and join you in the adventure.

  * You don’t take shortcuts. You’re speaking up for the future user, the edge case, the doomsday design. You know product engineers want to build it with you, and see them as allies, where you give them the power and knowledge to access greater things.

  * You’re someone who cares about what you do and the team you do it with, and want to work with others who do as well. You’ll be on interview panels choosing your next colleagues, and you’ll take that seriously. You only want to work with people who make you better, and want to make you better.

  * You’ve built infrastructure at a slightly later stage than Ashby is at - you know how to deal with millions of data points, have seen great (or not great) infrastructure make or break customer experience, and have automated everything from provisioning to monitoring and release process.

  * You’re a Swiss army knife (all nationalities welcome ;) ). You’ll be the third SRE, so you’ll get every hard problem the company faces. You’ll get to do infrastructure updates, security enforcements, database optimization, Kubernetes debugging, and digging through Typescript traces figuring out what doesn’t work. You probably don’t feel like an expert at at least some of that... and that appeals to you.

All that makes for a pretty specific kind of role, and the job isn’t to everyone’s tastes! You should not apply if:

  * You don’t want to make your own decisions on what is the best paved road to build for Ashby, and expect a lead or manager to make the final call on what that is. Our leads (and managers) give ample commentary and feedback on technical decisions and how they’re made, but you ship what you want to build and are accountable for it.

  * You hate SQL. We have a lot of features built around making the best out of data, and our platform engineers also sometimes dive into a gnarly report or advise engineers on a more performant data model to use.

  * You don’t want to code. Our SREs are some of our best software engineers and they are just as responsible for the application as the other engineering teams - albeit at a platform level. Reviewing code and submitting code changes will be part of your day to day.

  * Your primary mode of communicating best practices to engineers is live meetings. We’re a very async culture and written communication (and code) is how changes get made. As an Ashby SRE, you will need to share new tooling and best practices with engineers faster than your next meeting opportunity will take you.

  * You’ve never delivered a project, on your own, without someone prodding you for updates. We have no project or delivery managers to fill your calendar with busy work, but the flip side is you have to do your project management, seek the help you need to get unstuck and cut scope when it’s worthwhile.

# Technology Stack

I’m sharing our tech stack with the caveat that we don’t require previous experience in it: TypeScript (frontend & backend), Node.js, React, Apollo GraphQL, Postgres, Redis.

We use Datadog and Sentry on 100% cloud-based (AWS) infra. We take developer experience and reliability seriously: all engineers are on call in a follow-the-sun model, and everyone contributes to developer tooling.

# What We’re Building

Talent teams aspire to build a hiring process that identifies great candidates, moves them quickly through the interview process, and provides an excellent experience for the candidate. To accomplish this, recruiters perform thousands of daily tasks to coordinate and relay information between candidates, interviewers, and hiring managers. Teams struggle to keep up!

Scheduling a final round is an excellent example of our customers' challenges. A recruiter needs to collect availability from the candidate, identify potential interviewers, perform “Calendar Tetris” to find who is available to interview the candidate, schedule on the earliest date possible, and perform any last-minute adjustments as availability changes. They must perform this while considering the interview load on each individual and whether interviewers need to be trained and shadowing others. 🥵

Ashby provides talent teams with intelligent and powerful software that provides insights into where they’re failing and automates or simplifies many of the tasks they’re underwater with. We put a lot of effort into designing products that are approachable to beginners but mastered and extended by power users. In many ways, spreadsheets set the bar here.

We have many customers, great revenue growth, years of runway, and amazing investors like YCombinator, Elad Gil, and Lachy Groom. I’ll share more once we meet.

# Engineering Culture

Our engineering culture is motivated by Abhik and Benji’s (our co-founders) belief that a small talented team, given the right environment, can build high-quality software fast (and work regular hours!).

## Collaboration is Natural, Communication is Deliberate

Our engineering team (and the team at large) consists of lifelong learners who are humble and kind (meet them here!). These attributes create an environment where collaboration happens naturally (we filter for it in interviews). We combine this with research, prototyping, and written proposals to see around corners and get feedback from the team across time zones. Focus time is something that we hold sacred, and, with thoughtful and deliberate communication, engineers can focus 36h out of a 40h work week (Abhik wrote about it here). Even managers can rely on getting consistent time (and support to make, if necessary) to focus and do creative work without the demand of constant meetings.

## Increase Leverage, not Team Size

We built Ashby with the quality, breadth, and depth that many customers would expect from much larger teams over larger time scales. We’ve done this through investment in:

  *  **Great developer tooling.** Our CI/CD takes ~10m, and we deploy at least 5x a day. Everyone on the team has contributed to developer experience 💪🏾

  *  **Building blocks to create powerful and customizable products fast.** At the core of Ashby is a set of common components (analytics modeling and query language, policy engine, workflow engine, design system) which we are constantly improving. Each improvement to a common component cascades throughout our app (short video on it here).

Here’s an impromptu quote from Arjun in our company Slack of what it’s like to build a feature at Ashby:

![](https://app.ashbyhq.com/api/images/user-content/4ea5f68e-c33e-4ac9-831a-e732bee4a303/8d94727a-46d8-42a2-9627-ddcd7f822f95/arjun.png)

“Working on a generic framework for Surveys is really paying off! I was able to add the Automation Rules feature to EEOC Forms really quickly because I had some generic components and backend code. Took about 10 minutes and ~50 lines of code to do!”

## Give Engineers Ownership & Autonomy

We, as engineers, find clever ways to solve problems, which amplifies when we deeply understand the problem. All of us in technical leadership did our best work as engineers when we had a deep understanding of the end-user and the business and ownership over the solution. Our engineering culture reflects this experience: engineers own projects end-to-end, from speaking with users to writing product specs to UX design. These are skills that we often don’t get to practice as engineers, and, as a manager at Ashby, you’ll provide mentorship and feedback to engineers to ensure they are successful when delivering projects.

## Put Effort into Diversity

Diverse teams drive innovation and better outcomes. Having seen his mother and partner build their careers as minority women in non-diverse fields, Abhik wants to make sure Ashby creates opportunities for the next generation of engineers from underrepresented groups (including my daughter!).

Today, 26% of engineers at Ashby are from underrepresented groups. It’s not great, and we are taking conscious steps to improve, like sourcing diverse candidates, providing generous paid family leave, no leetcode interviews, and more.

# Interview Process

At Ashby, our team and interview process want to help you show your best self. We’ll dive into past projects and simulate working together via pair programming, writing tech specs collaboratively, and talking through decisions (no leetcode or whiteboard exercises). Our interview process is three rounds:

  1. 30-minute introduction call

  2. A technical screen (60-minute in-person)

  3. A virtual on-site of 2 hours and 45 minutes (can be split across two days) 

Our VP of Engineering, Abhik will be your main point of contact and prep you for interviews. You’ll meet your manager, 4 to 6 people in engineering (with 15 minutes in each interview to ask them questions) including our entire current SRE team. If we don’t give an offer, we’ll provide feedback!

# Your First Two Months at Ashby

We want an exceptional onboarding experience for every new hire. At Ashby, your dev environment sets up with a single script, you push your first change on day one, and we spend the rest of the time building your confidence in our codebase and practices culminating in the delivery of a prominent, impactful feature. We’ll pair you with a peer who’ll guide you through your first tasks and be someone you rely on, from answering questions to pair programming.

# Benefits

  * Competitive salary and equity.

  *  _10-year exercise window for stock options_. You shouldn’t feel pressure to purchase stock options if you leave Ashby —do it when you feel financially comfortable.

  * Unlimited PTO with four weeks recommended per year. Expect “Vacation?” in our one-on-one agenda until you start taking it 😅.

  *  _Twelve weeks of fully paid family leave in the US._ We plan to expand this to employees in other countries as situations arise.

  * Generous equipment, software, and office furniture budget. Get what you need to be happy and productive!

  * $100/month education budget with more expensive items (like conferences) covered with manager approval.

  * If you’re in the US, top-notch health insurance for you and your dependents with all premiums covered by us.

Ashby’s success hinges on hiring great people and creating an environment where we can be happy, feel challenged, and do our best work. We’re being deliberate about building that environment from the ground up. I hope that excites you enough to apply.

Ashby provides equal employment opportunities (EEO) to all employees and applicants for employment without regard to race, color, religion, sex, national origin, age, disability, genetics, sexual orientation, gender identity, or gender expression. We are committed to a diverse and inclusive workforce and welcome people from all backgrounds, experiences, perspectives, and abilities.

  
## CLICK TO [APPLY](https://www.remotewlb.com/apply/principal-platform-engineer-americas)

