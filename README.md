# Design Playbook :pencil:

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

		- [Overall UX Design Process](#overall-ux-design-process)
			- [Research](#research)
			- [Plan](#plan)
			- [Exploration](#exploration)
			- [Communicate](#communicate)
			- [Design](#design)
			- [Quality Assurance](#quality-assurance)
			- [Feedback](#feedback)
- [Research](#research)
	- [Kick off meeting](#kick-off-meeting)
	- [Existing website review](#existing-website-review)
		- [Heuristic Review](#heuristic-review)
			- [Scoring system](#scoring-system)
			- [Visualise](#visualise)
			- [Competitor Reviews](#competitor-reviews)
	- [Competitive Analysis](#competitive-analysis)
		- [Qualitative data](#qualitative-data)
			- [High-level inventories](#high-level-inventories)
			- [Labeling and taxonomies](#labeling-and-taxonomies)
			- [Visual Style](#visual-style)
			- [Strengths and area for improvement](#strengths-and-area-for-improvement)
		- [Quantitative Analysis](#quantitative-analysis)
			- [Ranking and rating](#ranking-and-rating)
			- [User performance](#user-performance)
			- [Search engine positioning](#search-engine-positioning)
- [PLAN](#plan)
	- [Personas](#personas)
		- [The process](#the-process)
		- [References](#references)

<!-- /TOC -->

#### Overall UX Design Process

Research --> Plan --> Exploration --> Communicate --> Design --> Quality Assurance --> Feedback

##### Research
  - [Kick off meeting questions](#kick-off-meeting)
  - [Existing website review](#existing-website-review)
  - [Competitive Analysis](#competitive-analysis) - See how others solve similar problems and try to not reinvent the wheel.
  - Data analysis - Do you have all the useful data you need? Try to have a look at funnels, clicks, page views, performances...
  - [User feedback](#user-feedback) - Always speak with Customer Care team! Don't have one? Check your old surveys or videos, what your customer says? What do they actually do?

##### Plan
  - [Personas](#personas)
  - [User stories](#user-stories) - *Have you done personas yet. If not DO IT NOW. Ok, now use them to write down user stories and scenarios.*
  - User flows - *Create your user's flow based on the scenarios you created, you can use it later to review the journey and create wireframes on top of each step.*
  - Red Routes - *Define red routes for your product and you’ll be able to identify, prioritise and eliminate any usability obstacles on key user journeys.*

##### Exploration
  - Brainstorm & Sketching - *Find a war room, fill it with markers and drinks, get together and sketch, discuss, vote, disrupt, have fun!*
  - Wireframes - *Add some details and structure to your ideas, reuse patterns and create pages on top of your user flows so you'll not leave anything behind.*
  - IA prototypes - *You can start creating paper prototypes and continuously iterate to more functional ones. Use sketches, HTML pages or static images, then just get some people and test.*

##### Communicate
  - IA - *Understand your users, your data structure and your channels. How can you organise your navigation and content in a clear and consistent way?*
  - Language - Follow your brand personality, keep in mind users' culture and language, the context of your product and make sure they understand you.
  - Accessibility - *You don’t need to add extra functionality or to duplicate any content. The key is simply to assess the requirements of those with different skills and limited devices.*

##### Design
  - Create
    - Style guide
    - UI Elements - Reuse elements and patterns, follow your style guidelines, don't have one? Create your guidelines. Start small, then create pages.
    - Gestures - *So you have a swipe slider? Tell me more about pinch, drag, zoom, rotate, shake, six-inch smartphones, left handed people, mouseover, kinect, motion detection...*
    - Responsiveness - *Can I see it on my mobile? Oh wait, what about my smart-watch which work as a remote for my 50" TV. Bonus: remember cross device experience.*
  - Give feedback
    - Waiting times - *If your users have to wait ages for the page to load, at least show them a loader, if take longer why don't you try something more entertaining?*
    - Errors - *Be clear and specific on what and where user's error is. I mean, your error, because if it's your fault you should say it.*
    - Completed actions - *Give immediate and clear feedback of successful user's actions. Do not always wait for server response, trust your server once in a while!*
  - Finalise
    - Finalise layout - *It's time to let your design shine, make it in the right way, don't stop with the first solution, always ask "is this the best you can do?"*
    - Use of images and icons - *Use of icons and images is strongly influenced by context, culture and layout that you use. Like icons, test your images, small changes can bring huge improvements.*
    - Font & colours hierarchy
      - *Use colours and font sizes properly, tryto follow your guidelines and keep it simple. The best visual hierarchies lead users to take the action confidently.*

##### Quality Assurance
  - Delight
    - Micro copy - *Every word is important, and a bit of personality will help your brand.*
    - Micro interactions - *Trigger, rules, feedback, loop. Details make the product. Bonus: Ever heard about easter eggs?*
    - Transitions - *Motion shouldn't be only beautiful, it should build meaning about the spatial relationships, functionality, and intention of the system.*
  - Speed tests/Errors
  - Finalise designs
  - Hand Off

##### Feedback
  - KPI testing - *What you want to achieve? What are your goals? Write down how you define success and failure and check if you have everything you need to collect the data.*
  - A/B testing - *Plan your AB test ahead and, if you can, plan a short roadmap of improvements. Your goal is not just improving KPIs, but learning something.*
  - Test - *UX lab, survey, sessions recording... test, observe and fix, test, observer and fix...*

  ---

## Research

### Kick off meeting

Questions to Ask at Kick-Off Meetings - taken from https://www.usability.gov/how-to-and-tools/resources/templates/questions-ask-kick-meetings.html

1.  Define **purpose/vision** for the site
  - What is the purpose of the site?
  - What are the goals of the site?
2.  Develop **goals** for the site
  - How would you define a successful website for your organization?
  - What does success look like? How will you know when you have been successful?
  - How would you describe the site?
  - From an organization’s viewpoint?
  - From a user’s viewpoint?
3.  Define **audiences** and **goals**
  - Who are the users of the site?  (Primary and secondary users)
  - How would you describe the users? (User characteristics, such as age, experience, education, etc.)
  - Why will they come to the site? (User needs, interests, and goals)
  - When and where will users access the site? (User environment and context)
  - How will users access the site? (User computer settings, such as connection speed, resolution, etc.)
4.  Conduct **task analysis** and **prioritize tasks**
  - What will users do on the site? (User tasks, content, features and functionality)
  - Which tasks are critical to users’ success on the website? (Criticality)
  - Which tasks are most important to users? (Importance)
  - Which features of the site will users use the most? (Frequency)
  - Which features are prone to usability issues? (Vulnerability)
  - Which tasks are critical to the organization’s success on the website?
  - How often will users frequent your website?
  - What will compel users to return to your website?
5.  Determine measurable **usability objectives**
  - Which tasks should users be able to accomplish easily with few errors? (Efficiency)
  - Which tasks should users be able to finish quickly and efficiently? (Effectiveness)
  - What level of satisfaction should users have after using the site? (Enjoyability)
6.  Discuss **expectations**, **requirements** and **preferences**
  - What is your vision of what the site should do?
  - How would you describe your initial view of the project? What do you think the project should entail?
  - What prompted the redesign?
  - Who will be the key point of contact?
  - Are there any restraints, mandates, or guidelines for the site?
  - Are there any sites you would like to model or a particular style that you prefer?
  - What characteristics/attributes/attitude should the site convey to users?
7.  Determine **accessibility requirements** and needs
  - Is the site currently accessible?
  - What type of accessibility testing has been done?
  - What types of accessibility tools are being used?
  - Who is the key point of contact on accessibility issues?
8.  Identify available **resources** and **training** needs
  - What level of resources is available for site updating and maintenance?
  - Do you have content writers skilled in writing for the Web?
  - Are there graphic designers on staff?
  - Who will be responsible for programming and maintaining the site?
  - Who is in charge of site marketing and promotion?
  - Who will be responsible for analyzing your site analytics?
  - Do you have a budget available for hiring or training staff?
9.  Discuss initial **technology needs**
  - What are your hosting needs?
  - Do you currently have a domain name or do you need a new one? Do you have the budget to buy a new domain name?
  - Are you currently using a content management system? If so, which one? If not, which systems are you currently looking at?
  - Are you currently logging Web metrics? If so, what metrics are you currently capturing? If not, do you plan on adding them to your site?
  - Do you currently have a search engine? If so, what type of search are you using?
  - Do you have a budget for implementing new technology?
10.  **Timeline** and **Project Plan**
  - Are there current mandates or deadlines in place requiring you to complete your project by a specific date?
  - Can you think of any issues that may arise that could delay your project completion? If so, do you have a plan for ensuring that the project moves forward?
  - When do you want to complete the project?
  - Do you have the available resources to complete your project on time?
  - Who will be responsible for managing the project plan and timeline?



### Existing website review

#### Heuristic Review

A review methodology should be used to avoid snap judgements. Also allows for the review process to be much much organised so that when doing this repeatedly, you remain consistent.

An approach to doing this is called a Heuristic Website Review, heuristic meaning the measurement of something that cant readily be quantified.

> NOTE: Do not just a website based on it's visual appeal. Sites like amazon, ebay, google and even facebook may not be visually appealing but functionally are perfect

Take into consideration these broad categories when exploring the website in detail:
- Task orientation and website functionality,
- Navigation and information architecture,
- Forms and data entry,
- Trust and credibility,
- Quality of writing and content,
- Search,
- Help, feedback and error tolerance,
- Page layout and visual/aesthetic design,
- Accessibility and technical design.

> Alternatively there are Jakob Nielsens's 10 general principles for interaction design:
- Visibility of system status
- Match between system and the real world
- User control and freedom
- Consistency and standards
- Error prevention
- Recognition rather than recall
- Flexibility and efficiency of use
- Aesthetic and minimalist design
- Help users recognise, diagnose and recover from errors
- Help and documentation


Use these broad categories to formulate a set of questions to repeatedly ask through the website. Example when reviewing the layout and visual design ask;
 *Are standard elements (such as page titles, website navigation, page navigation and privacy policy) easy to locate?*

##### Scoring system

Once you have devised your list of question addressing the above categories the idea is to score each of the categories using a points system.

  - 0 if it falls shorts
  - 1 if it's halway there
  - 2 if it does the job

Create a table using these sums like so:

| List item | Questions | Possible Score | Actual Score | Result |
|-----------|-----------|----------------|--------------|--------|
| Home page | 20        | 40             |  38          | 95%    |
| Task Orientation | 35 | 70 | 67 | 96% |
| Overall score | 288 | 383 | 457 | 95% |

##### Visualise

It's handy to visualise these strengths and weaknesses using a radar diagram. Problem areas or bias becomes instantly identifiable.

##### Competitor Reviews

A useful way to identify weaknesses in the market and point of difference opportunities is to complete a heuristic review on competitor websites, and place them up against each.


### Competitive Analysis

Competitive analysis is the exploration of the companies industry sector or market niche. The level of depth and detail of analysis into these competitors is up to you, based on time available. You can either do a broad high-level analysis or a top-5 style low-level analysis.

There 4 main benefits from completing a competitive analysis:

**You will understand the competition**

See what the other guys are doing, what are they offering to their customers, if their target audience the same and if not where does it differ and what can you do to create or maintain a compeitive advantage.

**You can build your domain knowledge**

Collating references of other sites in the industry will inform those working on the project, teaching them about content and functionality that they may not have considered.

**Identify best practices**

Looking at your competitors websites enables you to see what is working for them and what is being commonly offered on the web in that industry.

If all your competitors are offering feature A and feature B, users will expect your site to also house those features. If they are absent, users may go to the competitors.

Main goals from your competitive analysis should be:
- Learn from your competitors mistakes
- Avoid reinventing the wheel
- Find a better implementation from where they left off

**Expand the dialogue and the possibilities**

Finally, analysing your competitors expands the dialogue within the development team and can inform your strategic direction. New options may be found, if all the other guys are taking various approaches, and hence no standard approach exists.

#### Qualitative data
##### High-level inventories

| | Competitor 1 | Competitor 2 | Competitor 3 |
|-|-|-|-|
| Feature 1 | Y |   | Y |
| Feature 2 |   | Y |   |
| Feature 3 | Y | Y | Y |

##### Labeling and taxonomies

For projects involving hundreds of pages, the focus would expand beyond the inventory to analyzing hierarchy and labeling.

##### Visual Style

The graphic design of the competitor websites/web applications sets an immediate tone for the user experience and communicates professionalism, credibility, and usability.

##### Strengths and area for improvement

A useful starting point for identifying strengths and areas for improvement can be user experience heuristics.

The heuristics that I typically use are:

- Efficient Navigation
- Organizational Clarity
- Clear Labeling
- Consistent Design
- Matching User Expectations
- Effective Visual Design
- Supporting Readability & Scannability
- Facilitating User Tasks
- Providing Help

The strengths become discussion points and possibilities for emulation and improvement.Areas for improvement put the focus on competitive advantage, as they represent competitor shortcomings as well as pitfalls to be avoided.

#### Quantitative Analysis

##### Ranking and rating

One approach in the quantitative analysis is to rank and rate competitors. Competitors can be assigned a score for each of the heuristics, which then results in individual and aggregate measures of the user experience for comparison purposes.

##### User performance

If user testing is conducted, various metrics can be assessed. These include time on task, number of clicks to destination, path to destination, errors, and success rates.

##### Search engine positioning

A final area for analysis is ranking in major search engines, which could expand into an examination of marketing efforts by the competitors. There should be a set of common keywords for companies in the same market space, and top placement is a definite advantage in attracting new users.

## PLAN

### Personas

Creating personas is an important part of the research and planning stages as it prevents you from making the mistaking of thinking that something else is all about you.

It is recommended to create at least 3-5 web personas, focused on qualitative assessment, like a story about your persona.

#### The process

1. Create a persona document including information:
  - Name
  - Description
  - Photo
2. Refer to them based on their description e.g. "analytical influencer"
3. Include a longer description that focuses on what that person values and the way they make decisions. As well as some personal information
4. Precision is more important than accuracy. Make is realistic.
5. To test - use and act out the decision making scenarios
  - Search engine query
  - Follow their path from your landing page to your low level detail and responding to the call to actions

There are two basic types: decision makers and influencers.

**Decision makers** (most specific web personas) - type of person who is looking to buy a product or service. They are looking fro a solution to a immediate problem and quickly. They are looking for:
- Key facts
- Specific benefits
- Pricing
- Clear CTA

**Influencers** - gather information in order to help them make decision. One day they might become decision makers, but not right now. They are looking for informational content:
- Blogs
- Articles
- Whitepapers
- Webinars
- Customer forums
- CTA - to subscribe to content or register for events

Consider two basic behavioral personas when planning the IA:
- User browsing oriented - tend twoard exploring a sites menus in order to gain understanding of content
- Search oriented - immediately use a websites search function to find what they are looking for





---

#### References

- https://uxchecklist.github.io/
- http://www.smashingmagazine.com/2011/12/16/a-guide-to-heuristic-website-reviews/
