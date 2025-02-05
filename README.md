# Good Things

A compilation of good sensory things in life. Live site: https://mygoodthings.netlify.app

Built with [Eleventy](https://www.11ty.dev/docs/).

## To build

0. Install [Node](https://nodejs.org/) :)
1. Clone the repo
2. Run `npm install`
3. Run `npx @11ty/eleventy --serve`
4. Visit `localhost:8080`

## Commands

| Command                    | Purpose                      |
| -------------------------- | ---------------------------- |
| npm run start              | Serve project + watch Sass   |

## Adjustments for hosting your own version

If you’d like to host your own version of this list:

1. In `_data > site.json`, update the values to match your own environment. The `baseUrl` value should match the base URL at which your site will be hosted, including the scheme and excluding a trailing `/`. This will be used within the social media card image value.
2. If you change the aesthetic, don’t forget to change `/assets/images/social-media-card.png` to match your own styles.
3. `.github > workflows > daily-build.yml` defines a workflow that will trigger a daily build on Netlify. You can adjust this file to your liking, and update your fork repo to host your own private build key (refer to [“Scheduling Netlify deploys with GitHub Actions”](https://www.voorhoede.nl/en/blog/scheduling-netlify-deploys-with-github-actions/) for details). You may alternatively remove this file/directory.