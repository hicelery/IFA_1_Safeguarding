# IFA_1_Safeguarding

## 📋 Project Overview

A static website to give clear, easy-to-understand information on safeguarding practices, including how to recognize and respond to safeguarding concerns. Focus: simplicity, call to action, ease of information dissemination.

A project plan and outline:

-   Project workflow and repo setup
-   Creation of user stories
-   Wireframe skeleton and high priority features
-   development, smoke testing, deployment
-   in situe testing, performance and improvements

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

## Deployment and workflow

This project is deployed through github pages and follows a simplified agile gitflow methodology. Main branch is preserved as the deployed and live branch, whilst all development work will be conducted on feature branches. Code deployments to the live project environment will only available through a pull request to main.
All feautures must be tested on the 'develop' branch before being considered a release candidate to main. This ensures the deployed project maintains a stable codebase, and provides a scaleable workflow should the project scope increase and more developers were required to join the project.

<img width="600" height="600" alt="gitflow" src="https://github.com/user-attachments/assets/cb90c618-31c4-4622-a640-f5c324d0d7a1" />
