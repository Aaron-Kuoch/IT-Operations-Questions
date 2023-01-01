# IT-Operations-Questions

## In business or technical terms describe your understanding of continuous integration and continuous delivery (CI/CD)?

Continuous integration (CI) is a software development practice where a developer implements small code changes into a controlled repository and an automated test is run to identify bugs and errors. If the test does not identify any problems with the new code, the developer can proceed to make other changes if needed. However, if there is an issue, it is the duty of the developer to fix the new code before continuing. The use of continuous integration is essential in software projects, especially if you are working in a team. This is because it minimises the number of conflicts when merging one person's code with others, and thus, maximises the speed of completing the application. Moreover, most, if not all features in an application will run successfully without having to wait for problems to occur when the application is live. Continuous delivery (CD) is a practice that comes after continuous integration. Once the new code has successfully been implemented into the code base, the code is automated into different environments for testing, development and production. This is a major advantage for developers as they do not have to waste time deploying the software into any environment. This allows them to test for any bugs faster and thus deliver more frequent updates to their application which generally results in higher customer satisfaction. When these tests are successful and ready to be deployed, it must be manually done by a user. For the deployment to be done automatically, continuous deployment must be utilized. There is no difference between continuous delivery and deployment other than the fact that continuous delivery requires a user to deploy the change and continuous deployment does not require one.

## What are some tools that are used for this and why are they used?

A CI/CD pipeline tool is required to employ the features of CI and CD. One such tool is Jenkins. It is a popular tool for software developers due to it being free and available to many operating systems. But its main advantage compared to other tools is that it is an open-source platform and thus, has the capability to integrate with nearly any external software program (plugins) that is used for developing applications. Because of this, users have access to almost all plugins that suit their needs. The one disadvantage of having access to many plugins is that many may not be reliable due to them being made by open-source contributors and may not be tested for bugs. Another popular tool is Teamcity. Teamcity utilizes .NET technology better than any other CI/CD tools which makes it an attractive choice for developers who want to build their own plugins. With a variety of set functions like detailed history reports, status monitoring, source control and build chains, it allows users to better manage and track their work. However, with its complex user interface (UI), it can be intimidating to many new users and requires some studying before being able to fully make use of Teamcity. CircleCI is one of the most used CI/CD tools where even well-known clients like Spotify and Samsung use it. This is because CircleCI possesses a well-structured analytics board that allows the user to monitor and analyze jobs in real-time. Furthermore, it has reusable configuration packages called Orbs which speeds up the process of setting up pipelines. Thus, making it a noteworthy tool for developers who are looking to accelerate their CI/CD processes. The one downside to CircleCI is that it users will need to know YAML (Yet Another Markup Language or YAML Ain't Markup Language) which means it is not suitable for users with little experience with coding.

## Sources

https://www.youtube.com/watch?v=YGYoYSR-d98

https://www.atlassian.com/continuous-delivery/continuous-integration

https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment

https://www.infoworld.com/article/3271126/what-is-cicd-continuous-integration-and-continuous-delivery-explained.html

https://www.redhat.com/en/topics/devops/what-is-ci-cd

https://www.altexsoft.com/blog/engineering/cicd-tools-comparison/
