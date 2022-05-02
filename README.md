# <img src="https://bhilaihacks.netlify.app/405dce40772b68064041afdb07d9e584.png" width="22px">  Bhilai Hacks Cover Machine

[![GitHub license](https://img.shields.io/github/license/pranjalbareth/cover-machine.svg?style=flat&logo=github)](https://github.com/pranjalbareth/cover-machine/blob/master/LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat&logo=github)](https://github.com/pranjalbareth/cover-machine/pulls) ![Buildi](https://img.shields.io/badge/Build-Passing-brightgreen)

**A service that generates dynamic Covers & [Open Graph](https://ogp.me/) images for Bhilai Hacks Hackathon.**

# ✨ How To Use

### As a og-Image :
Use the generated image URL in the `<head>` of your HTML document as the og:image meta property

```html
  <meta property="og:image" content="https://og.railway.app/api/image?fileType=png&layoutName=Simple&Text=**Hello**+_World_" />
```

Whenever this image is requested (e.g. in link previews) the image will be generated on demand.

### As a cover
Download the Image in PNG/JPEG and use it for free.

# 🧐 How It Works

Images are generated through the `/api/image` route. When you hit this route the following happens
- Query params are parsed
- HTML page built, rendered with Puppeteer, and screenshot
- Screenshot returned with a long cache max age

# 🚀 Development

You can fork this repo, customize, and use in your own projects.

The frontend is a [NextJS](https://nextjs.org) site and the image generation happens in an API route.

```
# Install all dependencies
yarn 

# Start local development server
yarn dev

# Build for production
yarn build

# Start in production
yarn start
```

# 🙌 Acknowledgement

Credit where credit is due. This started as a forked repo from [Vercel's OG image generator](https://github.com/vercel/og-image). 
## Author 

|                                                                                         <a href="https://linkedin.com/in/pranjalbareth"><img src="https://raw.githubusercontent.com/pranjalbareth/pranjalbareth/master/1651233561082.jpeg" width="150px " height="150px" /></a>                                                                                         |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                        **[Pranjal Bareth](https://github.com/pranjalbareth)**                                                                                                                                        |
| <a href="https://twitter.com/pranjalbareth"><img src="https://raw.githubusercontent.com/vinitshahdeo/Water-Monitoring-System/master/assets/twitter.png" width="32px" height="32px"></a> <a href="https://www.facebook.com/pranjal.bareth"><img src="https://raw.githubusercontent.com/vinitshahdeo/Water-Monitoring-System/master/assets/facebook.png" width="32px" height="32px"></a> <a href="https://www.linkedin.com/in/pranjalbareth/"><img src="https://raw.githubusercontent.com/vinitshahdeo/Water-Monitoring-System/master/assets/linkedin.png" width="32px" height="32px"></a> |

## Support

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/pranjalbareth) [![GitHub followers](https://img.shields.io/github/followers/pranjalbareth.svg?label=pranjalbareth&logo=github)](https://github.com/pranjalbareth/)

Thank you for being here! 

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/pranjalbareth)

