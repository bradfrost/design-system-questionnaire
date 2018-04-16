# Design System Questionnaire
A one-page questionnaire to help your organization establish effective design systems and style guides.

# Why
- **Why do you want to create a design system?** What problems does the design system need to address in your organization?

## Goals
- **What are the goals you want to accomplish in establishing a design system?** - The [benefits of design systems](http://atomicdesign.bradfrost.com/chapter-1/#style-guide-benefits) are many, but what specifically are the goals of your organization's design system initiative?
- What will happen if this initiative fails?

---------------

# What
- **What is the name of the design system?** - A catchy and memorable name can help your design system gain traction. The name of the design system should embody the spirit of the organization and the system's underlying design principles. Fair warning: naming is hard. 

## What does the design system include?
**A design system is a collection of components, guidelines, documentation, points of view, processes, and tools.** What ingredients should your organization's design system contain? No doubt your organization's structure, processes, and tools will all influence the design system's ingredients. I recommend checking out Nathan Curtis's [Picking Parts, People, and Products](https://medium.com/eightshapes-llc/picking-parts-products-people-a06721e81742#.iy6eas2rw) for a great exercise to help prioritize what the system should include. 

Let's take a look at some of the parts that your design system can include:

## Brand Identity
- **Where are brand identity guidelines managed?** - These  include brand-wide elements such as logo, typography, color, tagline, marketing guidelines, etc.
- **What is the relationship between the overall brand identity and UI components?** - There may be a tight relationship between the brand guidelines and UI (i.e. buttons and logo are, and must be, the same color) or there may be a loose relationship (i.e. Material Design's guidelines and Google's brand guidelines are quite different).
- **Are you using any third-party tools or services to manage brand assets?** - Some of these tools include:
  - [Brand.ai](http://brand.ai/)
  - [Frontify](https://frontify.com/)
  
## Principles
- **What design principles does your design system embrace?** Design principles underpin every aspect of the design system, and influence its construction. They should jive with your organization's broader mission and culture, and your design principles should be easily understood by everyone doing work with the design system.

Here are some good resources about design principles:
- [Styleguides.io examples](http://styleguides.io/examples.html) - Many public style guides showcase their design principles
- [Design Principles FTW](http://www.designprinciplesftw.com/) - A big collection of design principles.
- [Design principle roundup](https://principles.adactio.com/) by Jeremy Keith rounds up a ton of principles from a ton of different fields.
- [Creating Design Principles](https://articles.uie.com/creating-design-principles/) - Jared Spool talks about the qualities of effective design principles.
- [Shaping Our Design Principles](https://medium.com/building-creative-market/shaping-our-design-principles-3474d6f5204b)

## High-level Guidelines
What are some high-level guidelines you want to provide in the design system? Some examples may include:

- Accessibility
- Animation
- Data display
- Data entry
- Data validation
- Multi-device design
- Layout
- Navigation
- Performance

While these topics will manifest themselves in more concrete ways at the component level, it's often a good idea to explicitly express the organization's point of view on these topics at a high level.

## Content
- **Do you have over-arching content strategy guidelines in place?**
- **Do you follow writing guidelines?** - What conventions should people writing on behalf of your organization follow? Check out [Dalhousie University's writing for the web](https://www.dal.ca/webteam/web_style_guide/writing_for_the_web.html) guide for a great example.
- **Do you have voice and tone guidelines in place?** - What qualities does your brand's 
embrace? How does your brand's tone change based on audience, context, and environment? The answers to these questions should be embodied in the voice and tone guidelines. For inspiration, check out:
  - [MailChimp's Voice and Tone](http://voiceandtone.com/)
  - [MailChimp's Content Style Guide](http://styleguide.mailchimp.com/voice-and-tone/)
  - [Voice and tone guidelines on Styleguides.io](http://styleguides.io/examples.html#voiceandtone) - 
  - [The Most Misunderstood Part of a Design System](https://medium.com/@alanweibel/the-most-misunderstood-part-of-a-design-system-fba520c1d292#.b1gju74ny)
  - [Take a closer look at the patterns in our language.](https://clearleft.com/posts/442) - Great article by Clearleft about establishing voice and tone principles and applying them to a product.
- **Microcopy** - How does the team write effective [microcopy](https://uxplanet.org/microcopy-tiny-words-with-a-huge-ux-impact-90140acc6e42#.pxaae93xy) together? 

## Color
- Brand colors
- Application colors
- Neutral palette
- Accessibility guidelines - [Design a Light & Dark Color System](https://medium.com/eightshapes-llc/light-dark-9f8ea42c9081#.mn7exfyhf)

## Typography

## Icons and Imagery
- **How are icons served in your products?** Icon fonts? Inline SVG? SVG sprites? PNGs?
- **Where are icons sourced?** In house or third party? Open source or proprietary? 
- **What’s the process for updating an icon in the system?**
- **What tools are used to create and manage icons?** This includes graphics programs like Illustrator and Sketch, but also icon management services like [Icomoon](https://icomoon.io/).   

## Motion
- **What are your guidelines for using motion and animation in your design system?** [Animation in your style guide](http://valhead.com/2015/07/09/animation-in-your-style-guide/)

## UI Components
- **What UI components are included in the system?** - Form fields, cards, tabs, and much more can be present in your organization's design system. Which UI components that  [Conducting an interface inventory](http://bradfrost.com/blog/post/conducting-an-interface-inventory/) can be a good way to determine which UI components should be codified in the design system.
- **Does your team use a methodology to organize components?** Such as [atomic design](http://atomicdesign.bradfrost.com/chapter-2/#the-atomic-design-methodology)?

## Page templates
- **What page templates should be included in the design system?** Are there common page templates your organization creates time and time again? Templates for portals, dashboards, homepages, blog posts, etc may be good to codify 

## Workflows
If UI components are the tools in the toolshed, then workflows are the common tasks you perform with those tools.

- **What workflows should be included in the design system?** Sign up
  - Authentication
  - Ecommerce checkout
  - Multi-step form

## Code Guidelines
- Frontend guidelines - For more information, check out my [Frontend Guidelines Questionnaire](https://github.com/bradfrost/frontend-guidelines-questionnaire) that's similar in format to this questionnaire.
- **Code language style guides** - Which backend technologies are in use at your organization (PHP, Ruby, .NET? Are there style guides available to help the team write more cohesive code together? 

## Tools
- **Static design tools?** UI toolkits for Sketch, Photoshop, etc

---------------

# People
- **Who are the primary users of the design system?** Who are the people that will be primarily be implementing the system's components, reading guidelines, and referencing the information in the style guide?
- **Who are the secondary users of the design system?** Secondary users are people who may not rely on the system for their day-to-day work but may find the docuementation and information in the style guide useful.
- **Are there teams or people in the organization that won't use the design system?** Why? What do they do instead?
- **Who are the prmimary [design system makers](http://atomicdesign.bradfrost.com/chapter-5/#design-system-makers)?** - Who is responsible for creating and maintaining the design system? Provide names and roles. 
- **How is the design system team structured?** Solidatary? Centralized? Federated? How the design system team is structured influences its adoptation and ongoing success. For more info, read: 
  - [Team Models for Scaling a Design System Team](https://medium.com/eightshapes-llc/team-models-for-scaling-a-design-system-2cf9d03be6a0#.u9d11mefp)
  - [The Salesforce Team Model for Scaling a Design System](https://medium.com/salesforce-ux/the-salesforce-team-model-for-scaling-a-design-system-d89c2a2d404b#.akuqars3c)
  - [Establishing a Design System Team](http://atomicdesign.bradfrost.com/chapter-5/#establishing-a-design-system-team) 
- **Who is the primary owner of the design system?** - Who is the primary person responsible for the design system's success or failure? This person is often in a senior leadership or director position.
- **Who is responsible for allocating time, budget, and resources to the design system initiative?**
- **Who are the key stakeholders in the design systems?** - "The stakeholder concept emerged in a 1963 internal memoran- dum at the Stanford Research Institute. It de ned stakeholders as “those groups without whose support the organization would cease to exist.” Your research should include anyone without whose support your project will fail. This might include executives, managers, subject matter experts, as well as sta  in various roles." -Erika Hall
- **Who are secondary stakeholders?** - Are there other people who either have 
- **Are there third parties involved?** - Are there any players outside of the organization (agencies, consultants, who will affect or be affected by the design system?

----------

# Products
- **What products will the design system serve?** - List the products the design system will be applied to. 
- **Are there products that will not be served by the design system?** Why? What will those products use instead? List the products that won't make use of the design system and discuss why they won't utilize the design system.
- **What are the design system's pilot projects?** - Pilot projects are often used to simultaneously create the pieces of the  design system while implementing the new patterns. Are there projects that should be used to construct the design system? Keep in mind that pilot projects should provide a cross-section of 
- **What technologies does the design system apply to?** (Web, iOS, Android, Windows, etc) - Different products and organizations use different technologies. Is the design system only relevant to your organization's web properties?

---------------

# Deployment
- **How are design system's components deployed into applications?** See
[Chasing the Holy Grail: Strategies For Distributing Your Pattern Library and Keeping It in Sync](https://medium.com/@marcelosomers/chasing-the-holy-grail-bbc0b7cce365#.3gjztlqve) for various strategies on how to deploy
- **How is versioning handled?** - What versioning conventions do you adhere to when rolling out new updates to the design system. See [Semantic Versioning](http://semver.org/) for an example.
- **How are dependencies managed?** 

---------------

# Communication
- **What communication channels are used to talk about the design system?** - The design system should plug into the organization's existing communication structure. Slack? Yammer? HipChat? Basecamp? Wikis? Blogs? Email newsletters?
- **What steps are taken when the design system is updated?** Release notes? Blog post? Email newsletter? Smoke signals?
- **How are system changes communicated to end users?** How are users of your organization's applications notified when design system changes affect their experience? This may include release notes, blog posts, guided tours, videos, overlays, tweets, etc.

---------------

# Contributing 
- **Who can contribute to the design system?** - Can every user directly contribute patterns or modifications to the design system's components and guidelines? Or is it only managed by a select few? On the spectrum from wipe open to complete lockdown, where does your design system stand?
- **What does the contributing process look like?** - Pull requests? Simple feature requests? Prototypes? What process should people expect to follow in order to propose fixing a bug, extending a pattern, adding a new  
See [modifying patterns](http://atomicdesign.bradfrost.com/chapter-5/#making-changes-to-patterns) for more info.

---------------

# Style Guide
- **Where does the style guide live?** - The style guide (the container that houses the guts of the design system) should live at an easy-to-access and easy-to-remember URL.
- **Is your style guide publicly accessible?** (Yes, no, maybe, eventually). Making a style guide public [has many benefits](http://atomicdesign.bradfrost.com/chapter-5/#make-it-public).
- **Are you using a [pattern library tool](http://styleguides.io/tools.html) to house your style guide?** - What tech is your style guide built on? What's its relationship to the 
