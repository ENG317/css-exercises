# @media Query Practice

Usually, we shoudl design and plan our site out with wireframes for each desired breakpoint. But, that's not always the situation. Sometimes, you have code that needs to be translated across breakpoints.

In your teams, create a mobile-first approach to `@media` queries to translate your studies of site into a mobile-first design.

1. Isolate and create the appropriate *breakpoint* scopes.
    - Does it currently works well on a 320px wide viewport?
    - If not, at what pixel width does the design "break"?
2. If it breaks before 320px, note it and consider what size screen it could be considered across Phones, Tablets, and laptops/desktops+.
    - Refer back to Mobile-First Google Slides: https://docs.google.com/presentation/d/14jpJPfZCXuEe0x3Kd8ql4Xd8DJ4g62k1/edit?usp=sharing&ouid=106375923921921850595&rtpof=true&sd=true
    - See the Internet Wayback Machine's archived version of this great resource: [screensiz.es](https://web.archive.org/web/20251203195433/https://screensiz.es/) for breakpoints to use.
3. Write your @media queries with `only screen and (min-width: xxxpx)` ranges.
4. Write or move code within its appropriate @media condition.

## How to Submit

When your work is complete as a team, each person will submit a simple link to the repo in Moodle.