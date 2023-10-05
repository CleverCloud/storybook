This is a [Storybook](https://storybook.js.org) demo by Clever Cloud.

This project is configured in a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

The app uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## 🚀 Deploy on Clever Cloud
 
 Storybook is deployed easily on a Node.js runtime on Clever Cloud. No add-on is needed.

 [📖 Check our Node.js documentation for further configuration](https://www.clever-cloud.com/doc/deploy/application/javascript/by-framework/nodejs/)

### Port configuration

 Apps on Clever Cloud need to listen on port 8080. Port already has been configured in this repo. To change yours in your project, go to `package.json` and change the `-p` argument.

 ```json
 "scripts": {
    ...
    "storybook": "storybook dev -p 8080",
    ...
 }
 ```

### Environment variable

 Make sure you inject this environment variable: `CC_RUN_COMMAND="npm run storybook"`

[📖 Check all environment variables your can use on Clever Cloud](https://www.clever-cloud.com/doc/reference/reference-environment-variables/)
