### Hi there 👋

My name is Jarrod Lilkendey, I am a software engineer based in Geelong, Australia.

### Portfolio

- 🕘 I built a [time tracker](https://168hoursapp.com) web application using NextJS: [repo](https://github.com/programmablewealth/168-hours), [docs](https://jarrodlilkendey.com/168-hours/)
- 📈 I built a [productivity](https://nextactionslist.com) web application based on the book Getting Things Done by David Allen using NextJS: [repo](https://github.com/programmablewealth/gtd-saas), [docs](tbd)

#### 168 Hours App

- Try out the [168 Hours App time tracker](https://168hoursapp.com)
- The application uses the following Tech Stack; React with NextJS, Typescript, Tailwind CSS, NextAuth and Prisma
- The goal of this project was to gain further experience with NextJS with the focus of building it in a way that is fully testable
- The secondary goal was to gain experience self hosting a NextJS application outside of Vercel
- React Testing library is used for Unit testing
- Cypress is used for running integration and E2E tests
- next-test-api-route-handler is used for integration testing on API routes
- Jest is used as a Test Runner
- The application is built into a Docker image and is hosted on a Digital Ocean VPS
- The Digital Ocean VPS hosts more than one of my web applications in different Docker containers and NGINX proxy manager is used as a reverse proxy which uses the hostname to proxy through to the Docker container
- DNS records are managed through CloudFlare and incoming web traffic to the Digital Ocean Droplet is whitelisted for only CloudFlare's IP addresses for DDoS mitigation
- GitHub Actions is used for CI/CD
- Monitoring is setup via Uptime Kuma that runs within my homelab, which every 60 seconds verifies the website is up and the TLS certificate is valid
- The Digital Ocean VPS is running Ubuntu Server operating system that I self manage. I use an Ansible playbook for downloading and installing the latest packages to keep the operating system up to date. Using Semaphore UI in my homelab, I have configured this Ansible playbook to run once a day using Cron over SSH.

<!--
**programmablewealth/programmablewealth** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
