---
layout: page
title: "Shiftr.io"
description: "Transfer events to Shiftr.io."
date: 2017-07-16 07:00
sidebar: true
comments: false
sharing: true
footer: true
logo: shiftr.png
ha_category: "History"
featured: false
ha_release: 0.48
---

The `shiftr` component makes it possible to transfer details collected with Home Assistant to [Shiftr.io](https://shiftr.io) and visualize the flow of the information. Keep in mind that your details will be public!

Create a new [namespace](https://shiftr.io/new) and generate a new token. You will need to use `Key (Username)` and `Secret (Password)` to setup the component.

To use the `shiftr` component in your installation, add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
shiftr:
  username: 63d8187f
  password: 32fd92de6a59c3e2
```

Configuration variables:

- **username** (*Required*): Username for the namespace.
- **password** (*Required*): Password for the namespace.

