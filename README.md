# IFA_1_Safeguarding

## 📋 Project Overview

A static website to give clear, easy-to-understand information on safeguarding practices, including how to recognize and respond to safeguarding concerns. Focus: simplicity, call to action, ease of information dissemination.

A project plan and outline:

-   Project workflow and repo setup
-   Creation of user stories
-   Wireframe skeleton and high priority features
-   development, smoke testing, deployment
-   in situe testing, performance and improvements

## User Stories

### User story 1

## Project Goals

This project aims to use a sleek and bold design to highlight only the most important information.

My target user group for this website are young adults. This will require a website that makes information approachable and reassuring, but does not belittle the user.

To do this, I will lean into bold and simplistic design language, that is widely present in media that targets this user group.
References and inspirations include:
https://talktofrank.com/

https://www.180studios.com/
<img width="1702" height="1322" alt="landing page for 180 studios" src="https://github.com/user-attachments/assets/53b588b4-c5ce-49db-b610-026ec2606e99" />

https://www.loopearplugs.com/
<img width="1704" height="1324" alt="landing page for an ecommerce site" src="https://github.com/user-attachments/assets/ee62aa16-ec55-4d37-9db9-45e69c57daf1" />

## Solution Design Details

I will create a large and impactful landing hero, with a call-to-action button. This will set the tone for the website and allow an immediate re-direct for users that need safeguarding help. The main content of the page will appear immediately below this, encouraging the user to scroll.
This image will use lower-quality/file size for smaller breakpoint screens to speed loading.

The main content will use a bootstrap contrain to make our 3 content sections responsive, each with 2 cards grouped by background colour.
For desktops this will show as a 2x3 grid, and fold to a single 1x6 column on tablets and below.
<img width="1456" height="986" alt="image" src="https://github.com/user-attachments/assets/12c85a70-d213-43ac-b118-ed42ffcc53ef" />

These will be full width and borderless to give the page a seamless feel.

Immediately following a the 'action steps' a CTA with an external redirect is presented, giving the user immediate help should they need. This remains at 100% width across all screens to keep this as proximal as possible.

Further information and additional resources are then presented, as this is less time sensitive than a user needing safeguarding assistance.

## Testing

Preliminary smoke testing was conducted on a local live server, before deploying tested features to the hosted website on github pages.

I used HTML and CSS validators, which highlighted any accessibility issues and one missing src attribute for navbar logo.

Following deployment to live, I manually tested functionality against my user stories, and noted some responsive sizing issues, and an issue with navbar functionality. After recording these in my project board, I deployed fixes leveraging AI for more involved changes.

The first pass lighthouse testing results are as follows:
<img width="1566" height="1040" alt="image" src="https://github.com/user-attachments/assets/c6563e6b-7761-4da2-9953-9db7ba0e950d" />
<img width="728" height="985" alt="image" src="https://github.com/user-attachments/assets/307c4449-1275-4719-a491-fd011e612fe9" />

<img width="760" height="928" alt="image" src="https://github.com/user-attachments/assets/627de51a-89f6-4319-9463-dc02cf6c9fa0" />



From this, we can see already our website is performant and accessible, due to leveraging webp assets and good use of semantic HTML. The largest suggested improvements come from external code libraries (bootstrap and google fonts), and the hosting service used (github pages). These are not appropriate improvements for the scope of this project. Actionable changes suggested focus on improving image delivery: many assets are saved as png and can have the resolution lowered without visible effect.

In future I would endeavour to use webp fileformat for a greater number of images.

## Deployment and workflow

This project is deployed through github pages and follows a simplified agile gitflow methodology. Main branch is preserved as the deployed and live branch, whilst all development work will be conducted on feature branches. Code deployments to the live project environment will only available through a pull request to main.
All feautures must be tested on the 'develop' branch before being considered a release candidate to main. This ensures the deployed project maintains a stable codebase, and provides a scaleable workflow should the project scope increase and more developers were required to join the project.

<img width="600" height="600" alt="gitflow" src="https://github.com/user-attachments/assets/cb90c618-31c4-4622-a640-f5c324d0d7a1" />

## Use of AI in development and project retrospective.

I have used LLM AI tools to stream line the development process with the following features:

-   Uploading website wireframe to create a boilerplate for the page structure
-   Creation of image assets
-   Inline edits with github copilot to autocomplete content.
-   Debugging bootstrap grid layout issues through copilot inline chat.
-   Refactoring completed code.

These streamedline the more repetitive development tasks, and in particular building a boilerplate from a wireframe very quickly set up a working base to allow me to concentrate on content and feature development. However, I noticed the models did struggle with mark up and comments present on the wireframe, so some manual intervention was required to have this functioning correctly.

Image creation allowed me to draw a rough draft in paint, and use copilot to render this as a professional quality asset quickly and with no cost. Content updates were highly impactful uses of AI in this project from an efficiency perspective, but I note generative text in particular is not a widely deployable use case for commercial sites.

Using copilot in IDE for debugging overflow issues saved a wealth of time. I described the issue and this returned a debug js script that would highlight the problematic elements, allowing me to much faster diagnose the root cause.

I had also used copilot to refactor sections of completed code in order to create quick mock-ups of layout changes. This enabled me to accelerate design decisions before applying the finishing styling tweaks.

In future projects I would continue to leverage AI for debugging, asset creation and code refactoring. These represent the largest and most universally applicable uses present in my project. Whilst an initial boilerplate certainly saved time on this project, as project size and complexities increase there will be a greater propensity for AI to make mistakes and fail to accurately recreate the wireframe content. This would be particularly apparent when showing the same screen multiple times on a wireframe describe a user journey (e.g clicking a button that expands a section).

## Use of external resources

https://cssgradient.io/ - To generate css code for background gradients
https://unsplash.com/ - For hero image assets

No other external code was used in this project.
