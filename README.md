# Phil's professional website - phil.city

### Why?
I opted to create my website from scratch for a few reasons:
1. To highlight my expertise with design, frontend development, and deployment
2. To maintain complete control over the appearance and functionality of the design
3. Hosting a static website is more affordable than building a solution with a WYSIWG editor such as Squarespace or Wix, and GitHub Pages makes it easy to manage

As it is now, the stack is absolutely excessive for the complexity of design, but it allows me to easily extend the website as needed down the road. For example, I may add a portfolio gallery in the future.

### How does it work?
The website was built using Svelte, Vite, and TailwindCSS.

Svelte is a modern JavaScript framework with some of the highest developer satisfaction rates because of its elegant design, terrific performance, and superb documentation. I'm a big fan!

I like using Tailwind CSS in certain situations because I find that it simplifies my approach to styling and prevents situations where I need to hunt down where a particular element is being styled.

Changes pushed to GitHub automatically trigger a build that produces static web files, which are then uploaded to GitHub pages. The deployment script is in `.github/workflows`.
