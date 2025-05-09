# Overview

> Share your Replit Apps with the world in just a few clicks.

Replit Deployments lets you publish your Replit App to the cloud using a simplified process.

## What is Replit Deployments?

Replit Deployments is a feature that saves a **snapshot** of your Replit App to the cloud,
where it everyone can interact with it. A snapshot captures the current state of the files in your
Replit App.

When you deploy your Replit App, you create a **deployment**. A deployment is a running instance
of your app on Replit's cloud infrastructure. This makes the app reliably available on the internet,
separate from the version in your workspace.

<Info>
  Replit's infrastructure is backed by Google Cloud Platform (GCP). All deployments are hosted in the United States.
</Info>

Replit Deployments includes tools to monitor your deployment status and view web analytics.

Replit offers the following deployment types:

<CardGroup>
  <Card title="Autoscale Deployments" href="/cloud-services/deployments/autoscale-deployments" icon="layer-group">
    Automatically adjusts resources based on your app's usage.
  </Card>

  <Card title="Static Deployments" href="/cloud-services/deployments/static-deployments" icon="files">
    Provides an affordable way to host websites that don't change based on user input.
  </Card>

  <Card title="Reserved VM Deployments" href="/cloud-services/deployments/reserved-vm-deployments" icon="server">
    Provides a consistent amount of computing resources for your app to run continuously.
  </Card>

  <Card title="Scheduled Deployments" href="/cloud-services/deployments/scheduled-deployments" icon="clock">
    Runs your app at scheduled times that you choose.
  </Card>
</CardGroup>

## Getting started

Follow the steps below to deploy your Replit App:

1. From your Replit App workspace, select <img class="icon-svg" src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/shared/deploy-icon.svg" alt="Deployment icon" /> **Deploy** at the top.
2. In the **Deployments** tab, select your deployment option.
3. If **Add a payment method** appears, follow the prompts to add a payment method.

Replit automatically selects the best deployment option for your app based on the project type and your needs.

However, to choose a different deployment type, consider the following information.

<Accordion title="Choose the right deployment option for your app">
  The following video explains how to choose the right deployment option for your app:

  <Frame>
    <iframe src="https://www.youtube.com/embed/sXP5d0k1atk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen />
  </Frame>

  Use the following decision tree featured in the video to help you choose:

  <Frame>
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/deployments/deploying-your-repl/choose-your-deployment.png" alt="Diagram explaining how to choose a deployment option" />
  </Frame>
</Accordion>

## Key features

Deployments offer the following convenient features:

* **Multiple deployment types**: Select or update a deployment type that meets your needs in a few clicks.
* **Custom domains**: Serve your app from your web domain.
* **Analytics**: Track visitor data and other metrics for your deployed app.
* **Monitoring tools**: View your app's deployment status and configuration.
* **Access controls**: Control who can see your app with a single click. Available only for **Teams** members.

## How it works

When you deploy your Replit App, Replit creates a snapshot of your app's files and dependencies.
This snapshot is then sent to Replit's cloud infrastructure, where it runs as a separate instance of your app.
To update your deployment with the latest changes, deploy again to create a fresh snapshot.

<Warning>
  Avoid saving and relying on data written to a deployed app's filesystem. To store data, use a storage or database option such as Replit's [Storage and Database](/category/storage-and-databases) offerings.
</Warning>

## Use cases

The following examples show different types of Replit Deployments.

### Autoscale deployment: Typing speed assessment app

Let the cloud scale up resources when users take typing tests and reduce them when not in use.

### Static deployment: Solar system simulation

Learn about the planets in a solar system visualization app on the web.
This visualization renders in the browser and doesn't transfer any user input to a server.

### Reserved VM deployment: Discord bot

Run a Discord bot that helps you moderate and onboard members.
It's always online to chat with users and respond to commands with predictable pricing and performance.

### Scheduled deployment: Home automation triggers

Schedule API calls to start and stop your smart home devices at specific times and days.

## Next steps

To learn more about Replit Deployments, see the following resources:

* [Autoscale Deployments](/cloud-services/deployments/autoscale-deployments/): Learn how to set up applications that scale with traffic
* [Static Deployments](/cloud-services/deployments/static-deployments/): Discover how to deploy static websites quickly and efficiently
* [Reserved VM Deployments](/cloud-services/deployments/reserved-vm-deployments/): Explore dedicated VM options for specialized use cases
* [Scheduled Deployments](/cloud-services/deployments/scheduled-deployments/): Set up recurring tasks with simple scheduling
* [Custom Domains](/cloud-services/deployments/custom-domains/): Connect your deployment to a custom domain
