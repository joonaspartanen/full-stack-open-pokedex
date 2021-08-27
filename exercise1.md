# Exercise 11.1

Let's consider an application build with [Gatsby](https://www.gatsbyjs.com/). We could use TypeScript, but let's say that our language of choice for this exercise is JavaScript.

## Linting

For linting we could use ESLint or Prettier, both supported by Gatsby. Using linter is always useful for writing clean code, but it is especially important in team projects to guarantee that all developers follow the same rules.

In the case of Gatsby, we can take advantage of its built-in ESLint setup which can be customized according to needs and wishes of the developer team. It is important to agree on certain rules and conventions to follow already in the beginning of the project.

## Testing

Developing a Gatsby application doesn't differ that much from developing a regular React application, so we can take advantage of our favorite React test tools and libraries, such as Jest for unit tests and Cypress for E2E tests.

Setting up Jest for Gatsby requires some additional configuration, but luckily there's a [good documentation](https://www.gatsbyjs.com/docs/how-to/testing/unit-testing/) for that.

## Building

Bundling and transpiling our application is easy because Gatsby uses webpack and Babel and, in many cases, the default configuration is totally fine. For more special needs, the configuration can naturally be modified both manually or using one of the many plugins available for Gatsby, which can often be an easier path.

## Hosting

Gatsby is a static site generator and using a cloud environment to host a Gatsby site is often the most simple choice, though hosting the site on a dedicated server is definitely possible too.

We can choose among pretty much any cloud service provider, such as Azure or AWS, but Netflify seems to be a popular (and cheap) choice particularly for Gatsby sites.

Gatsby also provides its own cloud service, Gatsby Cloud, for hosting Gatsby sites. Gatsby Cloud offers many attractive functionalities, such as incremental and preview builds, that allow us reduce the time needed to update and preview our site (building larger Gatsby projects is not always fast).
