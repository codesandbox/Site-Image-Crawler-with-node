# Site-Image-crawler

This is web crawler built using cheerio js and node-fetch.

## What is a web crawler?

This is a program or automated script which browses the World Wide Web in a methodical, automated manner. 

## What does this particular web crawler do?

It goes through a site, identifies all the link paths and gets back the images on each link page. Right now these links are logged to the console and the files are created in you filesystem. You can extend this application and save to a downloadable folder. 

## Usage 

Add the site URL you want to crawl images for at the end of the functions

```
crawl({
	url: "", // Add Site URL here
     });

```

## Resources
- Add your [configuration](https://codesandbox.io/docs/projects/learn/setting-up/tasks) to optimize it for [CodeSandbox](https://codesandbox.io/p/dashboard).
- [CodeSandbox Projects — Docs](https://codesandbox.io/docs/projects)
- [CodeSandbox — Discord](https://discord.gg/Ggarp3pX5H)
