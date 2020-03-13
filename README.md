<p align="center">

  ![Pixie!](pixie_banner_light.png)

  <p align="center">
    Live-debug distributed environments with <a href="https://work.withpixie.ai/">Pixie</a>
  </p>

</p>

---

Pixie is being built to give engineers access to no-instrumentation, streaming & unsampled auto-telemetry to debug performance issues in real-time. 

Pixie's magical developer experience is enabled by three key design attributes:

1. **No Instrumentation Collection:** Full-body network requests (via eBPF), metrics, logs & events collected without the need for code-changes and at less than 5% overhead. 
2. **Edge Compute:**  Data storage and computation isolated within the customer's kubernetes cluster without the need to persist data outside the customer's environment.
3. **Command Driven Consumption:** Data and signals programmatically accessed via the Pixie UI or Pixie CLI which are powered by an expressive API. 

We're building up Pixie for broad use by the end of 2020 with an initial focus on Kubernetes workloads. 

_If you are interesting in tinkering with our beta,  feel free to [sign-up](https://withpixie.ai/) and join our [community on slack](https://join.slack.com/t/pixie-community/shared_invite/enQtODY3NjU5MTc4OTY0LTFhYjc3MWY1NDBkZTc5YTdjNzM0OGYxZmNmODU2MDE5NzYyN2Q1NmIxMmEyN2YwNmM5MjU4NGY2NDBjOWFjY2E). If you want to learn more about use check out our [company overview deck](https://docsend.com/view/kj38d76)._


<details>
  <summary><strong>Table of contents</strong></summary>

- [Quick Start](#quick-start)
- [Demos](#Demos)
- [Contributing](#contributing)
- [About Us](#about-us)
</details>


## Quick start

1. **Create account**

    Visit our [product page](https://work.withpixie.ai/) and signup with your google account. 

2. **Install**

    Copy and run this command to install the CLI in your environment.

    `bash -c "$(curl -fsSL https://withpixie.ai/install.sh)"`

3. **Deploy**

    Run this to deploy PEMs and the Pixie Command Module in your K8s cluster.

    `px deploy`

4. **Lift off! 🚀**

    Start using the CLI by running `px help` in your termina or view your preconfigured view in the Live UI at `https://work.withpixie.ai/`

_For detailed information on compatibility & requirements check out our [docs](https://work.withpixie.ai/docs/getting-started/compatibility-requirements) or  ping us on [slack](https://join.slack.com/t/pixie-community/shared_invite/enQtODY3NjU5MTc4OTY0LTFhYjc3MWY1NDBkZTc5YTdjNzM0OGYxZmNmODU2MDE5NzYyN2Q1NmIxMmEyN2YwNmM5MjU4NGY2NDBjOWFjY2E)_


## Demos

**Install walkthrough**

[![Pixie Deploy Overview](https://img.youtube.com/vi/KYjBKiJWQbw/0.jpg)](https://www.youtube.com/watch?v=KYjBKiJWQbw)


**Use `px` to run scripts**

![CLI Demo](./cli_demo.svg)


_For more demos, check out our  [youtube](https://www.youtube.com/channel/UCOMCDRvBVNIS0lCyOmst7eg/videos)._ 

## Contributing

- **Bugs:** Something not working as expected? [Send a bug report](https://github.com/pixie-labs/pixie/issues/new?template=Bug_report.md).
- **Features:** Need new Pixie capabilities? [Send a feature request](https://github.com/pixie-labs/pixie/issues/new?template=Feature_request.md).
- **Views & Scripts:** Need help building a live views or pxl scripts? [Send a live view request](https://github.com/pixie-labs/pixie/issues/new?template=Live_view_request.md).
- **Development:**  Pixie is a SaaS product and not open-core. We do plan to open-source sub-components but we're not there yet as we're heads down building. In the interim, if you are interested in contributing, [Email us](mailto:community@pixielabs.ai).
- **Community:** Interested in becoming a Pixienaut and in helping shape our community? [Email us](mailto:community@pixielabs.ai).


## Resources

- [Documentation](https://work.withpixie.ai/docs)
- [Community Slack](https://join.slack.com/t/pixie-community/shared_invite/enQtODY3NjU5MTc4OTY0LTFhYjc3MWY1NDBkZTc5YTdjNzM0OGYxZmNmODU2MDE5NzYyN2Q1NmIxMmEyN2YwNmM5MjU4NGY2NDBjOWFjY2E)
- [Issue Tracker](https://github.com/pixie-labs/pixie/issues)
- [Youtube](https://www.youtube.com/channel/UCOMCDRvBVNIS0lCyOmst7eg/videos)
- [Overview Slide Deck](https://docsend.com/view/kj38d76)
- [Company Website](https://pixielabs.ai)

## About Us

Founded in late 2018, we are a San Francisco based stealth machine intelligence startup. Our north star is to build a new generation of intelligent products which empower developers to engineer the future.

We're heads down building Pixie and excited to share it broadly with the community later this year.  If you're interested in learning more about us or in our current job openings, we'd love to [hear from you](mailto:info@pixielabs.ai).
