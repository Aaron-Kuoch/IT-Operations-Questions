# IT-Operations-Questions

## In business or technical terms describe your understanding of continuous integration and continuous delivery (CI/CD)?

Continuous integration (CI) is a software development practice where a team implements new code into the code base. When a change is made, an automated test is run to identify bugs and errors in the new code. If the test does not identify any problems with the new code,  the developer can proceed to make other changes if needed. However, if there is an issue, it is the duty of the developer to fix the new code before continuing. The use of continuous integration is essential in software projects, especially if you are working in a team. This is because it minimises the number of conflicts when merging one person's code with others, and thus, maximises the speed of completing the application. Moreover, most, if not all features in an application will run successfully without having to wait for problems to occur when the application is live. 

Continuous delivery (CD) is a practice that comes after continuous integration. Once the new code has successfully been implemented into the code base, the code is automated into different environments for testing and/or production. This is a major advantage for developers as they do not have to waste time deploying the software into any environment as it is done automatically. This allows them to test for any bugs faster and thus devlier more frequent updates to their application which generally results in higher customer satisfaction. When these tests are successful and ready to be deployed, it must be manually done by a user. For the deployment to be done automatically, contiuous deployment must be used. There is no difference between continuous delivery and deployment other than the fact that continuous delivery requires a user to deploy the change and continuous deployment does not require one.

## What are some tools that are used for this and why are they used.

A tool that is used for CI/CD is Jenkins. It is a popular tool for software developers due to it being free and available to many operating systems. But its main advantage compared to other tools is that it has the capability to integrate with almost any external software program (plugins) that is used for developing applications. Because of this, users have access to almost all plugins that suit their needs. The one disadvantage of having access to many plugins is that it may not be reliable due to it being made by open source contributors and potentially have not tested them for bugs.

Another popular tool that is used is Teamcity. Teamcity utilizes .NET technology better than any other CI/CD tools which makes it an attractive choice for developers who want to build their own plugins. With its broad variety of set functions like detailed history reports, status monitoring, source control and build chains, it allows users to better manage and track their work. However, withs its complex user interface (UI), it can be intimidating to many new users and requires some studying before being able to fully make use of Teamcity.

CircleCI is one of the best CI/CD tools shown by some well known users such as Spotify and Samsung. It possesses a well structured analytics board that allows the user to monitor and analyze jobs live. CircleCI has reusable configuration packages called Orbs which aids in speeding up and simplifying pipelines. Thus, making it a noteworthy tool for developers who are looking to speed up their CI/CD processes. The one downside to CircleCI is that it users will need to know YAML (Yet Another Markup Language or YAML Ain't Markup Language) which means it is not suitable for users with little experience with coding.



## Sources

https://www.atlassian.com/continuous-delivery/continuous-integration

https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment

[https://www.youtube.com/watch?v=_zCyLT33moA](https://www.youtube.com/watch?v=YGYoYSR-d98)

https://www.altexsoft.com/blog/engineering/cicd-tools-comparison/#:~:text=Jenkins%20is%20an%20open%2Dsource,be%20your%20first%2Dchoice%20tool.

https://www.opsera.io/blog/ace-your-devops-game-with-this-ultimate-list-of-plugins-in-jenkins#:~:text=Plugins%20extend%20the%20functionalities%20and,in%20the%20CI%2FCD%20toolchain.

https://www.altexsoft.com/blog/engineering/cicd-tools-comparison/#:~:text=TeamCity%20works%20right%20after%20installation,have%20to%20duplicate%20your%20code.
