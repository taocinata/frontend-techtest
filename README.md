# Frontend Tech Test

This is a technical test to evaluate basic front-end development skills.

Please treat this task like you would any other task at work - feel free to search the web, and try to write code which is easily maintained by others.

This repo contains a template with a collection of social and other links that appear in a page sidebar. These links have a duplication of the link text in the title attribute. This is unnecessary, and must be removed. However, we still want a tooltip to appear when the images are hovered over.

This test uses a front-end application called Shunter that receives data in the form of JSON, and transforms it into HTML. You will need to read some of [the documentation](https://github.com/springernature/shunter) to complete the test. Part of the setup has been done for you, and you do not need to read all of the documentation. Focus specifically on the [templates/styling/javascript](https://github.com/springernature/shunter/blob/master/docs/getting-started.md#templates), [routing](https://github.com/springernature/shunter/blob/master/docs/usage/routing.md), [resources](https://github.com/springernature/shunter/blob/master/docs/usage/resources.md), and [layout](https://github.com/springernature/shunter/blob/master/docs/usage/templates.md#using-layouts) sections. You might also need to refer to the [dust.js](http://www.dustjs.com/) documentation.

Before we begin, you'll need to have [Node.js](https://nodejs.org/) installed, this test requires **Node.js 4.4.3+**

Steps
-----
1. Fork this repo
2. Clone your fork on the command line
3. Create and checkout a branch with your name in it e.g. `johnsmith`
4. Make sure the the correct version of Node.js is installed
5. Install dependencies with ```npm install```
6. Download, follow the instructions in the README and run the [backend application](https://github.com/springernature/frontend-techtest-backend) (no work should be needed in this repository)
7. Make any changes in this repository so that it can receive data from the backend application
8. Add images to the links provided in the example
9. Using the data provided, create a tooltip for each of the links, that appears when you hover the link
10. Submit a pull request with your changes

Acceptance criteria
-------------------
1. When hovering over the links, a tooltip should appear
2. Images should appear inline to the left of the links
3. There must be no duplication of content
4. The template should use the data being sent from the backend application
5. The solution must not interfere with standard browser behaviour
6. HTML and CSS must validate
7. The principles of Progressive Enhancement must not be violated
8. Browser support: IE9+, latest stable release of Chrome, Firefox, Safari
9. Must be easy to maintain

