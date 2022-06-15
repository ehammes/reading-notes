# Read: 02 - Express, NPM, TDD, CI/CD

## Reading

[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

1. **Explain middleware, answer as though I were a non-technical recruiter.** Middleware helps build applications more efficiently by providing common services/capabilities to apps outside of what's offered by the operating system. Middleware is between an operating system and the applications running on it.
2. **Express the most popular __ __ ____.** Express is the most popular framework based on the number of high profile companies that use it, the # of people contributing to the codebase, and the number of people providing both free and paid for support.
3. **Express is “unopinionated.” What does that mean?** Frameworks that have few restrictions on the best way to build components together to achieve a goal. This makes it easier for developers to use the most suitable tools to complete a particular task.
4. **What is a module and why is modularity useful to us as developers?** A Javascript file that can be imported into other code using Node's `require()` function. Modularity is useful to developers because it makes code easier to read, test, locate, and reuse.

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

1. **What version of npm are you running on your machine?** 8.6.0
2. **What command would you type to install a library/package called ‘jshint’ into your node project?** npm i jshint

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

1. **Explain why tests are important. Please explain as though I were your non technical elder.** Tests are important because it reduces the number of defects/bugs, streamlines team efficiency, and improves design qualities in the code.
2. **What are three expected benefits of testing** Reduction of defect rates, reduces required effort during the final phases of a project, and improves the technical quality of code
3. **Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.** Individual pitfalls include forgetting to run tests frequently and writing too many tests at once. Team mistakes include partial team adoption and poor maintenance of test suite.

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

1. **What are three benefits of Continuous Integration?** Three benefits of CI include ensuring everyone's changes integrate, catch defects/bugs, and reduce merge conflicts
2. **What is the difference between Continuous Delivery and Continuous Deployment?** Continuous Delivery allows development to release at any time while Continuous Deployment allows for new features to be deployed immediately
3. **Explain how GitHub fits into this process assuming the listener comes from a non-technical background** GitHub sends messages (webhooks) to external systems (servers) about activity that occurs in a project. GitHub helps manage, tracks, and communicates the changes to integrate.

### Bookmark and Review

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)