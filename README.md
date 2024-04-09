<p align="center">
  <a href="https://nitric.io">
    <img src="https://raw.githubusercontent.com/nitrictech/nitric/main/docs/assets/nitric-logo.svg" width="120" alt="Nitric Logo"/>
  </a>
</p>

<p align="center">
  A fast & fun way to build portable cloud-native applications
</p>

<p align="center">
  <img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/nitrictech/nitric?sort=semver">
  <a href="https://twitter.com/nitric_io">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/nitric_io?label=Follow&style=social">
  </a>
  <a href="https://nitric.io/chat"><img alt="Discord" src="https://img.shields.io/discord/955259353043173427?label=discord"></a>
</p>

## Project Description

This application monitors website uptime through event-driven mechanisms, utilizing APIs, scheduling, and Pub/Sub for asynchronous communication between services. When a website goes down or comes back up, it sends a Discord notification to alert users. The frontend is built with Astro/React.

<img src="./assets/frontend.png" alt="Frontend"/>

<img src="./assets/arch-diagram.png" alt="Diagram"/>

## Usage

### Step 1: Install Nitric

Follow the steps in the [installation guide](https://nitric.io/docs/installation)

### Step 2: Configure Environment Variables

- Create a `frontend/.env` from `frontend/.env.example` and update your base API URL as `NITRIC_API_BASE_URL`.

- Create a `.env` file from `.env.example` and add your [Discord Websocket URL](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks).

### Step 3: Run your Nitric project locally

```bash
yarn install
nitric start
```

### Step 4: Run your frontend locally

Inside the `/frontend` directory:

```bash
yarn install
yarn dev
```

## About Nitric

[Nitric](https://nitric.io) is a framework for rapid development of cloud-native and serverless applications. Define your apps in terms of the resources they need, then write the code for serverless function based APIs, event subscribers and scheduled jobs.

Apps built with Nitric can be deployed to AWS, Azure or Google Cloud all from the same code base so you can focus on your products, not your cloud provider.

Nitric makes it easy to:

- Create smart serverless functions and APIs
- Build reliable distributed apps that use events and/or queues
- Securely store and retrieve secrets
- Read and write files from buckets

## Documentation

The full documentation is available at [nitric.io/docs](https://nitric.io/docs).

We're completely open-source and encourage [code contributions](https://nitric.io/docs/contributions).

## Get in touch

- Ask questions in [GitHub discussions](https://github.com/nitrictech/nitric/discussions)

- Find us on [Twitter](https://twitter.com/nitric_io)

- Send us an [email](mailto:maintainers@nitric.io)

- Jump into our [Discord server](https://nitric.io/chat)
