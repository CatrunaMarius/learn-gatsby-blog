# 32. Bonus Build a GatsbyJS Blog
## Referince link
[Gatsby](https://www.gatsbyjs.com/)

[Gatsby blog starter](https://github.com/gatsbyjs/gatsby-starter-blog)

[Gatsby-CLI](https://www.gatsbyjs.com/docs/gatsby-cli/)

[Gatsby plugin library](https://www.gatsbyjs.com/plugins)

[useStaticQuery](https://www.gatsbyjs.com/docs/use-static-query/)

[pages documentation](https://www.gatsbyjs.com/docs/creating-and-modifying-pages/)

[Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[gatsby-transformer-remar]k(https://www.gatsbyjs.com/plugins/gatsby-transformer-remark/)

[gatsby-source-filesystem](https://www.gatsbyjs.com/plugins/gatsby-source-filesystem/)

[gatsby-node.js API documentation](https://www.gatsbyjs.com/docs/node-apis/)

[createFilePath](https://www.gatsbyjs.com/plugins/gatsby-source-filesystem/#createfilepath)

[createPage](https://www.gatsbyjs.com/docs/actions/#createPage)

[createPages](https://www.gatsbyjs.com/docs/node-apis/#createPages)

[Tagged template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#Tagged_templates)

[dangerouslySetInnerHTML](https://reactjs.org/docs/dom-elements.html#dangerouslysetinnerhtml]
(path)[https://nodejs.org/api/path.html)

[babel-plugin-styled-components npm](https://www.npmjs.com/package/babel-plugin-styled-components)

[gatsby-plugin-styled-components npm](https://www.npmjs.com/package/gatsby-plugin-styled-components)

[styled-components npm](https://www.npmjs.com/package/styled-components)

[netlify hosting](https://www.netlify.com/)
## GatsbyJS

Here's the truth: I am not the biggest fan of GatsbyJS. The reason is that it involves a lot of configuration and setup. It's one of those libraries that feels like you're learning something completely new instead of just writing Javascript. As you go through these codes, you might find yourself saying "this is so different than anything I have done before as a React developer". Don't get discouraged. GatsbyJS is a type of library that requires you to go through the documentation and sometimes learn a completely different way of structuring your code which is unique to Gastby. We decided to add this as a bonus to the course, but by no means should you feel let down if you don't get everything in these videos. Like I said, Gatsby is all about the "GastbyJS way", and if you don't understand it completely, it won't affect you outside of using GatsbyJS.

So focus more on creating a blog as a fun way to end the course instead of understanding every detail. As a professional React developer, you won't encounter these problems unless you are working directly with Gatsby.
<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's default starter
</h1>

Kick off your project with this default boilerplate. This starter ships with the main Gatsby configuration files you might need to get up and running blazing fast with the blazing fast app generator for React.

_Have another more specific idea? You may want to check out our vibrant collection of [official and community-created starters](https://www.gatsbyjs.com/docs/gatsby-starters/)._

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```shell
    # create a new Gatsby site using the default starter
    gatsby new my-default-starter https://github.com/gatsbyjs/gatsby-starter-default
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-default-starter/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.com/tutorial/part-five/#introducing-graphiql)._

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

3.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

4.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

5.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.com/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

6.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.com/docs/gatsby-config/) for more detail).

7.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.com/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

8.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.com/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

9.  **`LICENSE`**: This Gatsby starter is licensed under the 0BSD license. This means that you can see this file as a placeholder and replace it with your own license.

10. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.com/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.com/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/gatsbyjs/gatsby-starter-default)

<!-- AUTO-GENERATED-CONTENT:END -->
