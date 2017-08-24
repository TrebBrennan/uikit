# FAQs

The Frequently Asked Questions (FAQs) page contains answers to commonly raised queries about the design system.

If you can't find an answer to a question you have please email us at [guides@dta.gov.au](mailto:guides@dta.gov.au) or join our conversation on [slack](http://guides.service.gov.au/join-slack/).

## General

### Is there any documentation or list of components?

You can view our current [documentation here](http://uikit.apps.staging.digital.gov.au/). We are creating a new version which should make it easier to get started with the design system.

### What are you working on?

You can view our [project backlog](https://github.com/govau/uikit/projects/2) to see an up to date list of tasks. We generally try to balance 50% community engagement (capability uplift and understanding user needs) and 50% product (maintenance and building).

### What are the differences between version one and version two?

Version one was implemented following strict semantic HTML. This caused issues with implementation as users who didn't have easy control over their HTML struggled to implement the design system. Due to this version one is now deprecated and is no longer supported.

Version two uses classes that need to be added or extended onto HTML. This allows users to be more flexible with the HTML they are provided with.

### Who can use the design system?

The design system is built for everyone. We want government and private sector to embrace the Uikit. It aims to solve common usability and accessibility problems in a simple and robust way.

### What is the design system built for?

The design system is built to solve common usability and accessibility problems in a simple and robust way.

### I found an issue/bug/problem. What do I do?

Thats awesome! 

Please take a look at the Github [issue queue](https://github.com/govau/uikit/issues), if you find a relevant issue please join the conversation and note down any steps you took to find it. If it's a new issue please [create a new issue](https://github.com/govau/uikit/issues/new).

## Design

### Spacing of typography feels off?

The current spacing in the Uikit is going through a change which we hope to be implemented in the coming months. 

We are planning to move from using pixels on the uikit-space function to REMs. We are also moving to system fonts which will allow a consistent X-height, this will allow us to align our typography to a grid.

We are also investigating changing our typographic rhythm for the spacing under headers and paragraphs.

### Why do you use system fonts?

- System fonts have come a long way, major websites (github) and design systems (bootstrap) have embraced them. 
- Increasing load times for users is not worth the slightly nicer aesthetics 
- Using one font we are able to align our typography to a baseline grid

### Why is there a max-width on elements inside the body?

To optimise readability we have set a `max-width` on certain elements inside the body. This creates a consistent and easy to use user interface. You can override the code as necessary, but please understand your users needs.

### Are there .PSD or .Sketch files of the design system?

We currently do not provide and design files. In the future we would love to provide users with variations of files to allow them to access the latest components in the design system.

### Carousels, dropdowns and all of the fancy things?



## Developer

### Is the design system available with my content management system or javascript framework?


### Why are my HTML elements NOT automatically styled (h1, input, blockquote, etc.)?


### Why are the classes on the headings backwards? (.uikit-display-6 for H1)?


### Why should I use a design system if I still have to write custom code?


### What is pancake? Do I need to know pancake?


### How do I request a new component to be added to the system?


### How do I add the Uikit to my build process? How do I add custom code/variables/overrides?


### How do I make a pull request? What branch should I pull request into?


### What code standards do I need to follow for a pull request?


### Where can I get help implementing the design system with my project?


