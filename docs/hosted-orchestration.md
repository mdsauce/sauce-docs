---
id: hosted-orchestration
title: Hosted Orchestration (Beta)
sidebar_label: Getting Started
---

:::info
Hosted Orchestration is currently in Limited Beta. If you would like to participate please visit our [Product Portal](https://portal.productboard.com/sauceprod/2-sauce-labs-portal/c/32-hosted-test-orchestration)
:::

Hosted Orchestration runs mobile and browser tests up to 70% faster, from within the Sauce Labs grid via our container execution environment. All you need to do is package your test code as a Docker image and grant us access.

Hosted Orchestration is Sauce's attempt to beat latency. No matter what you're testing each command must travel from the Selenium/Appium client -> to the Sauce Labs grid -> back to the Selenium/Appium client. [These roundtrips take time](https://gist.github.com/hellerbarde/2843375), and depending on how close you are to our data centers there may be nothing you can do to speed up tests. Now you can run tests as if you were in our data center!

For example, a test with 500 commands and 200 milliseconds average roundtrip time would save almost 2 minutes running as a Hosted Orchestration test.
