---
title: Downsampler
github: 'https://github.com/PostHog/downsampling-plugin'
installUrl: 'https://app.posthog.com/project/apps?name=Downsampling'
thumbnail: >-
  https://res.cloudinary.com/dmukukwp6/image/upload/posthog.com/contents/cdp/thumbnails/downsampling.png
tags:
  - downsampler
---

import Requirements from "./_snippets/requirements.mdx"
import FeedbackQuestions from "./_snippets/feedback-questions.mdx"
import PostHogMaintained from "./_snippets/posthog-maintained.mdx"

> **Note**: We do not recommend using the downsampler to lower the number of events ingested by PostHog. Instead, we have guide you can use to [capture fewer unwanted events](/tutorials/fewer-unwanted-events).

This connector enables you to reduce how many events a deployment of PostHog will ingest. This is especially useful for users who have huge volumes of data, but don't need to analyze it all and want to avoid large bills.

<Requirements />

## Installation

1. In PostHog, click the "[Data pipeline](https://us.posthog.com/apps)" tab in the left sidebar.
2. Search for 'Downsampling' and select the connector, press Install.
3. Follow the on-screen steps to configure the connector.

## Configuration

<AppParameters />

## FAQ

### Is the source code for this connector available?

PostHog is open-source and so are all connectors on the platform. The [source code for the Downsampler connector](https://github.com/PostHog/downsampling-plugin) is available on GitHub.

### Who created this connector?

We'd like to thank PostHog team members [Michael Matloka](https://github.com/Twixes) and [Marius Andra](https://github.com/mariusandra) and [Neil Kakkar](https://github.com/neilkakkar) for creating the Downsampler.

<PostHogMaintained />

<FeedbackQuestions />
