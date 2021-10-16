# INT 2.1

[![Netlify Status](https://api.netlify.com/api/v1/badges/747a0ea7-f2a2-4a71-87d7-99493ad0e4a7/deploy-status)](https://app.netlify.com/sites/ashah/deploys)

## Description

Personal portfolio/blog site. Leverages [11ty](https://www.11ty.dev/) static site generator for high performance. Leverages [Netlify CMS](https://www.netlifycms.org/) for ease-of-use.

## Demo

Visit [ashah.netlify.app](https://ashah.netlify.app) to browse around.

Authentication for the admin panel should be invite-only. But for now, it's [publicly open](https://ashah.netlify.app/admin).

Feel free to sign up via email or GitHub OAuth to test the CMS by posting some sample blog posts.

Note: your log in credentials are **not** stored by the site. Authentication is managed professionally by Netlify's `Identity` authentication service. Additionally, all newly signed up users will be deleted anyway when the site is switched to an invite-only admin CMS.

## Technologies

The end-product is a simple static website. However, numerous technologies were involved in getting there:

- 11ty Static Site Generator
- Nunjucks HTML Templates
- Netlify CMS
- Netlify Identity for Admin Authentication
- Continuous Deployment on Netlify

## Acknowledgements

- [Kevin Powell](https://www.youtube.com/kepowob) for 11ty and Netlify tutorial
- [Logoipsum](https://logoipsum.com/) for logo
- [Unsplash/Lorem Picsum](unsplash.it) for images
