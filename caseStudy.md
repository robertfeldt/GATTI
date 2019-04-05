## Part 2. Case study - Find a software/lib that uses the testing tool (Jest)

**Q2.1. What is the purpose of the sw/lib, i.e. what does it aim to do for users/developers?**
Dasher Create flexible dashboards with GitHub queries.
This is a small application with only one contributor on GitHub but I thought that his test with Jest was interesting.

**Q2.2. What are the key technologies used to develop the lib?**

The main technologies used in the application are GraphQL, Javascript, Nexus, TypeScript, React, React-Appolo, Node.

**Q2.3. What kind of automated testing tools are used to test the sw/lib (including but possibly more than Jest tool) and what are their key features?**

Dasher is an application that uses Jest to mock Github tokens. After the Mock using Jest. The developer is doing some unit test with Jest to see if the value of the payload is correct depending on the input of the Mock Token.

The developer chose not to use other test frameworks. He also used some tools to test his graphql calls to have more robust software.
The asynchronous testing for graphQL call is another Jest feature that the developer chose to use.

The only test file is index.test.ts in the backend.

**Q2.4. Which features of the automated testing tools are currently used by the test suite?**

The application uses a useful and some time complex feature. This feature is Mocking.

Mock functions make it easy to test the links between code by erasing the actual implementation of a function, capturing calls to the function (and the parameters passed in those calls), capturing instances of constructor functions when instantiated with new, and allowing test-time configuration of return values. Definition took from https://jestjs.io/docs/en/mock-functions.

After this new value can be used to see the state of a payload and test other functions with this Mock data.

This is exactly what the developer of Dasher did. He faked the Token from Github to see the different behavior of his software with a valid and an invalid token.

The developer also made the decision to use Jest to test is asynchronous GraphQL calls.

**Q2.5. Which features of the automated testing tools are NOT used by the test suite?**

The application doesn't use a lot of features from Jest. It doesn't use the snapshot comparison feature for the front-end. Doesn't do a test on a Database using Jest and finally, he doesn't use Jest to do a test on his DOM.

## Part 3. Interview developers/testers of LambdaTest tool

**Q3.1. Reach out to the developers of LambdaTest tool and ask them about their reasons for developing LambdaTest tool. Why this particular type of testing technology? Which situations is it good for and less good for?**

I started working on Jest because it was slow, buggy and broken to the point that people stopped writing tests at Facebook and people lost confidence in the tool. I wanted to fix that.

**Q3.2 Ask them how mature they think LambdaTest tool is? Is it suitable for use by companies developing real-world software at scale? Why / why not?**

Jest is very mature. Every large company that writes frontend code is using or adopting it at this point.

We have a team of contributors from various companies who all drive the project forward and are continuously re-inventing it to make sure it keeps being relevant and useful.

**Q3.3. Ask them how they plan to evolve and develop LambdaTest tool going forward. What are the main improvements needed to take the tool to the next level?**

Jest always had a particular focus on user experience. A better testing experience will lead to people writing more tests. This is what sets Jest apart from all other test frameworks.

** Special thanks to Christoph Nakazawa, the main contributor to the Jest project, for taking the time to answer my questions.**