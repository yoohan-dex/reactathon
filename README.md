<p align="center">
  <img src="banner.png"/>
  :wavy_dash: React.js :wavy_dash: Relay.js :wavy_dash: React-Router :wavy_dash: React-Bootstrap :wavy_dash:<br />
  :wavy_dash: GraphQL :wavy_dash: Sequelize (SQL) :wavy_dash: Express.js :wavy_dash: Passport.js :wavy_dash: Babel.js :wavy_dash: Winston :wavy_dash:<br />
  :wavy_dash: PM2 :wavy_dash: Microsoft Azure :wavy_dash: Heroku :wavy_dash:
</p>

### Reactathon - Kickstart Your Next React-App  Project or Hackathon

Reactathon works out of the box to so you can get working on your next project quickly.

Its modern libraries and tools  provide a highly functional base for your project with minimal startup effort. 
Rapidly build and deploy an SEO-Ready WebApp with User Authentication and oAuth2 support using React, Relay, React-Router, Express, and much more!

Reactathon was inspired by [Hackathon Starter](https://github.com/sahat/hackathon-starter)
by [Sahat Yalkabov](https://github.com/sahat)


### Rapid start
These commands work out of the box without any issues. When they complete, you will have a working web application running in your browser. For details, see [Getting Started](#getting-started) and [FAQs](#faqs).

```sh
  git clone https://github.com/MattMcFarland/reactathon.git &&
  cd reactathon && npm install && npm run dev
```
### Current Roadmap:
This project is under active development, both to implement the TODOs (below) and to make sure that it installs easily, so you can get to work on your own additions to the project.

[View current tasks and TODOS in the issues board](https://github.com/MattMcFarland/reactathon/labels/TODO). The items below provide a high-level view of the project.
The following will be completed for the v1.0.0 release. We will be using SEMVER.

- [ ] Add an optional seeder that seeds the database with dummy data.
- [x] Add user profile page, dashboard page, and email support.
- [x] Add passport reset and passport forgot workflows.
- [ ] Add User posts and user follow actions / activities.
- [ ] Need a working unit test framework for clientside.

### Getting started

**1. Clone the Repo:**

```sh
git clone https://github.com/MattMcFarland/reactathon.git 
```

**2. Install Dependencies:**

```sh
cd reactathon
npm install
```

**3. Edit App config:**

Edit `server/src/app.config.js` to setup everything.

**4. Seed database:**

Optionally run the seeder to create dummy data.

```sh
npm run seed
```

**5. Run the dev server:**

```sh
npm run dev
```

**6. Deploy when ready:**

Deploy options are further down the guide :)

### FAQs

- **What bells and whistles does Reactathon include?**

	- React.js
	- Node.js
	- Express.js
	- Babel.js 6.3.x ES7 Stage 0
	- GraphQL
	- Relay ready
	- Sequelize SQL ORM
	- sqlite3 database
	- PhantomJS SEO
  	- Winston logging
	- Passport.js with oAuth2 support
		- SQL User database
		- Github
  		- Facebook
  		- Twitter
  		- Google Plus
	- Deployment with the following suites:
  		- PM2
  		- Microsoft Azure
  		- Heroku

- **What are the System Requirements?** Reactathon has been tested with:
	- Mac OSX or Linux
	- Node.js v5.3.0
	- Further testing needed to source our requirements

- **Are the warnings a concern?** During `npm install` you may see warnings about deprecated or global packages. These are expected, and will not cause a problem. Should they become a problem, the project will be updated as needed.

- **Are any of the bundled packages experimental?**

Reactathon currently uses babel stage zero, which is considered experimental.
As such, it is recommended to sustain upgrading babel until reactathon is
more stable.

### Changelog

- 0.10.2
  - Update readme
  - Update package.json

- 0.10.1
  - Add resolve dependency
  
- 0.10.0
  - Add nav items for articles
  
- 0.9.0
  - Add database seeder (Issue: #6)
  - Add article list view (Issue: #3)
  - Add article detail view (Issue #20)
  
- 0.8.1
  - Update readme

- 0.8.0
  
  - Add Password reset views
  - Add Password reset endpoint
  - Add mailgun emailer
  - Add server endpoint for reset/forgot
  
- 0.7.0

  - Add winston logger

- 0.6.x
  - 0.6.2 - Fix issue #16 (Slow dev startup)
  - 0.6.1 - update ecosystem.json to have correct value for development env
  - 0.6.0 - add link/unlink social provider functionality to the dashboard view

- 0.5.0
  - add start of user dashboard
  - add edge cases for signup and logout
  - add oauth for github, google, twitter, and facebook.
  - fix critical issue with missing files causing npm install to fail.

- 0.4.x
  - 0.4.1 - Fix relayJS
  - 0.4.0 - Add Github oauth2 flow

- 0.3.0
  - Added social media button styling
  - Added client auth login logic

- 0.2.0
  - added adobe illustrator file

- 0.1.0

  - Fixed critical issue with example env vars not loading
  - Improved watch script speed
  - Add Token to model

- 0.0.0 -- start

### License

The MIT License

### Acknowledgements

The idea of this hackathon starter project is heavily inspired from [Hackathon Starter](https://github.com/sahat/hackathon-starter) that was created by Sahat Yalkabov in 2014 and is still very much in active development.


