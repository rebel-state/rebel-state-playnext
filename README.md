<head>
<style>
.brandName {
  font-weight:bolder;
  color:orange;
}
</style>
</head>

<h1> Rebel State - Website</h1>

This is the offical repo for the <span class="brandName">Rebel State Frontend.</span> This serves as a gateway to the services, tooling and data stores that are part of the <span class="brandName">"State of Rebels"</span>

This project is currently in development. Features and functionality and even the proposed timetable is not guaranteed in any respect. This page is to serve as a roadmap of features and functionality and their development and completion dates in addition to development notes for configuration and design.


## Database Integration
 This site uses a postgrtes database managed by [Neon](https://neon.tech). It uses a db branching workflow that requires testing being built into it.  It also requires that the .env variables are added to github and included in its production deployment.

See the following resources for setup and configuration of the database
- [neon.tech console](https://console.neon.tech/app/projects)
- [neon integration with github](https://neon.tech/docs/guides/neon-github-integration)
- neon integration actions
- neon integration with prisma 
 
 ### Tasklist
 + [x] Setup Initial Documentation
 + [X] Setup Neon Console
 + [x] Setup Neon GitHub Branching
 + [x] Setup Neon GitHub Actions
 + [ ] Create actions code for PRs
 + [ ] Create actions code for merges
 + [ ] Setup Prisma in React
 + [ ] Create Unit Tests
 + [ ] Create Smoke Tests
 

 ## Authentication Setup
 This project uses NextJS for an oAuth authentication provider. Below are references and task lists for implementing this into the site.

 ### References
- [NextJS Auth]()
- [oAuth documentation]() 
- [oAuth Providers]()
- [Templates Integration of NextJS]() 

 ### Tasklist
 + [ ] Generate Env Properties
 + [ ] Set properties/secrets on github
 + [ ] Test Authentication
 + [ ] Setup Github Authentication
 + [ ] Setup Google Authentication
 + [ ] Test All Authentication
 + [ ] Create Unit and Feature Test cases


 ## Design Phase
 + [ ] Setup Storybook
 + [ ] Create Style Guide
 + [ ] Import and Create componets






