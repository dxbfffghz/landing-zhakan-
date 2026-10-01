## Responsive

### Phone — 375 px
![375](screenshots/375.png)

### Tablet — 768 px
![768](screenshots/768.png)

### Desktop — 1280 px
![1280](screenshots/1280.png)

## Why this tool

I used **Tailwind CSS via Play CDN** because it lets me build a full responsive layout directly in HTML without switching to a separate stylesheet. Writing classes like `grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3` right next to the markup makes the responsive behaviour obvious at a glance — I can see exactly where each breakpoint kicks in. The `md:` and `lg:` prefixes are compact and consistent, so I did not have to invent class names or write custom media queries. It does get in the way when the same long class list repeats across many elements: the markup becomes noisy, and any redesign means editing every card. Compared to Bootstrap, Tailwind gives me more control and no predefined look, but I have to write more utilities by hand. Compared to Sass+BEM it is faster for small projects, though it hides the CSS away in a CDN script and would not be how I build a large production site. Overall for a one-page landing page, Play CDN is the fastest way to get a clean, responsive result.

## AI tools used

Claude (Anthropic) — for the Tailwind conversion of my LAB 2 markup. Every class was reviewed and explained by me before submission.