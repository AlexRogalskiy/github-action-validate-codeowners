
<!-- markdownlint-disable -->
# GitHub Action to Validate CODEOWNERS

 [![Test Status](https://github.com/cloudposse/github-action-validate-codeowners/workflows/validate-codeowners/badge.svg?branch=main)](https://github.com/cloudposse/github-action-validate-codeowners/actions?query=workflow%3Avalidate-codeowners) [![Latest Release](https://img.shields.io/github/release/cloudposse/github-action-validate-codeowners.svg)](https://github.com/cloudposse/github-action-validate-codeowners/releases/latest) [![Slack Community](https://slack.cloudposse.com/badge.svg)](https://slack.cloudposse.com)
<!-- markdownlint-restore -->

[![README Header][readme_header_img]][readme_header_link]

[![Cloud Posse][logo]](https://cpco.io/homepage)

<!--




  ** DO NOT EDIT THIS FILE
  **
  ** This file was automatically generated by the `build-harness`.
  ** 1) Make all changes to `README.yaml`
  ** 2) Run `make init` (you only need to do this once)
  ** 3) Run`make readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **





-->

This is a Github Action to validate the `CODEOWNERS` file by running a series of checks against the `CODEOWNERS` file to ensure that it's valid and well-linted.

Ensuring your repository's `CODEOWNERS` file is valid can be critical to the development process if, for instance, your project uses [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) conditions that rely on definitions in `CODEOWNERS`.

---

This project is part of our comprehensive ["SweetOps"](https://cpco.io/sweetops) approach towards DevOps.
[<img align="right" title="Share via Email" src="https://docs.cloudposse.com/images/ionicons/ios-email-outline-2.0.1-16x16-999999.svg"/>][share_email]
[<img align="right" title="Share on Google+" src="https://docs.cloudposse.com/images/ionicons/social-googleplus-outline-2.0.1-16x16-999999.svg" />][share_googleplus]
[<img align="right" title="Share on Facebook" src="https://docs.cloudposse.com/images/ionicons/social-facebook-outline-2.0.1-16x16-999999.svg" />][share_facebook]
[<img align="right" title="Share on Reddit" src="https://docs.cloudposse.com/images/ionicons/social-reddit-outline-2.0.1-16x16-999999.svg" />][share_reddit]
[<img align="right" title="Share on LinkedIn" src="https://docs.cloudposse.com/images/ionicons/social-linkedin-outline-2.0.1-16x16-999999.svg" />][share_linkedin]
[<img align="right" title="Share on Twitter" src="https://docs.cloudposse.com/images/ionicons/social-twitter-outline-2.0.1-16x16-999999.svg" />][share_twitter]




It's 100% Open Source and licensed under the [APACHE2](LICENSE).
















## Usage



Copy the `.github/workflows/validate-codeowners.yml` file from this repository into the `.github/workflows` folder of the repository to which you'd like to add Validate `CODEOWNERS` functionality, and ensure that you are using an appropriate token in the workflow file.
This will cause the validation functionality to execute whenever any event occurs on any pull request.

## Quick Start

Here's how to get started...
1. Copy the `.github/workflows/validate-codeowners.yml` file from this repository into the `.github/workflows` folder of the repository to which you'd like to add Validate CODEOWNERS functionality.
2. Replace `${{ secrets.CODEOWNERS_VALIDATOR_TOKEN_PUBLIC }}` with the name of a token whose permissions are in line with your target repo's requirements, according to the instructions [here](https://github.com/mszostok/codeowners-validator/blob/main/docs/gh-token.md).


## Examples

Here's a real world example:
- [`github-action-validate-codeowners`](https://github.com/cloudposse/github-action-validate-codeowners/.github/workflows/validate-codeowners.yml) - Cloud Posse's self-testing Validate CODEOWNERS GitHub Action





## Share the Love

Like this project? Please give it a ★ on [our GitHub](https://github.com/cloudposse/github-action-validate-codeowners)! (it helps us **a lot**)

Are you using this project or any of our other projects? Consider [leaving a testimonial][testimonial]. =)



## Related Projects

Check out these related projects.

- [GitHub Action Auto-format](https://github.com/cloudposse/github-action-auto-format) - Add standard files to a repo and keep its README up to date
- [GitHub Action Auto-release](https://github.com/cloudposse/github-action-auto-release) - Automatically draft release notes for a new release when merges are made into the default branch
- [GitHub Action Terraform Auto-context](https://github.com/cloudposse/github-action-terraform-auto-context) - Automatically update `context.tf` whenever a new version becomes available
- [GitHub Action Terraform CI](https://github.com/cloudposse/github-action-terraform-ci) - Full suite of Terraform CI actions, along with chatops support


## References

For additional context, refer to some of these links.

- [Codeowners Validator](https://github.com/mszostok/codeowners-validator) - A GitHub Action that validates the `CODEOWNERS` file in a repo


## Help

**Got a question?** We got answers.

File a GitHub [issue](https://github.com/cloudposse/github-action-validate-codeowners/issues), send us an [email][email] or join our [Slack Community][slack].

[![README Commercial Support][readme_commercial_support_img]][readme_commercial_support_link]

## DevOps Accelerator for Startups


We are a [**DevOps Accelerator**][commercial_support]. We'll help you build your cloud infrastructure from the ground up so you can own it. Then we'll show you how to operate it and stick around for as long as you need us.

[![Learn More](https://img.shields.io/badge/learn%20more-success.svg?style=for-the-badge)][commercial_support]

Work directly with our team of DevOps experts via email, slack, and video conferencing.

We deliver 10x the value for a fraction of the cost of a full-time engineer. Our track record is not even funny. If you want things done right and you need it done FAST, then we're your best bet.

- **Reference Architecture.** You'll get everything you need from the ground up built using 100% infrastructure as code.
- **Release Engineering.** You'll have end-to-end CI/CD with unlimited staging environments.
- **Site Reliability Engineering.** You'll have total visibility into your apps and microservices.
- **Security Baseline.** You'll have built-in governance with accountability and audit logs for all changes.
- **GitOps.** You'll be able to operate your infrastructure via Pull Requests.
- **Training.** You'll receive hands-on training so your team can operate what we build.
- **Questions.** You'll have a direct line of communication between our teams via a Shared Slack channel.
- **Troubleshooting.** You'll get help to triage when things aren't working.
- **Code Reviews.** You'll receive constructive feedback on Pull Requests.
- **Bug Fixes.** We'll rapidly work with you to fix any bugs in our projects.

## Slack Community

Join our [Open Source Community][slack] on Slack. It's **FREE** for everyone! Our "SweetOps" community is where you get to talk with others who share a similar vision for how to rollout and manage infrastructure. This is the best place to talk shop, ask questions, solicit feedback, and work together as a community to build totally *sweet* infrastructure.

## Discourse Forums

Participate in our [Discourse Forums][discourse]. Here you'll find answers to commonly asked questions. Most questions will be related to the enormous number of projects we support on our GitHub. Come here to collaborate on answers, find solutions, and get ideas about the products and services we value. It only takes a minute to get started! Just sign in with SSO using your GitHub account.

## Newsletter

Sign up for [our newsletter][newsletter] that covers everything on our technology radar.  Receive updates on what we're up to on GitHub as well as awesome new projects we discover.

## Office Hours

[Join us every Wednesday via Zoom][office_hours] for our weekly "Lunch & Learn" sessions. It's **FREE** for everyone!

[![zoom](https://img.cloudposse.com/fit-in/200x200/https://cloudposse.com/wp-content/uploads/2019/08/Powered-by-Zoom.png")][office_hours]

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/cloudposse/github-action-validate-codeowners/issues) to report any bugs or file feature requests.

### Developing

If you are interested in being a contributor and want to get involved in developing this project or [help out](https://cpco.io/help-out) with our other projects, we would love to hear from you! Shoot us an [email][email].

In general, PRs are welcome. We follow the typical "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull Request** so that we can review your changes

**NOTE:** Be sure to merge the latest changes from "upstream" before making a pull request!



## Copyrights

Copyright © 2022-2022 [Cloud Posse, LLC](https://cloudposse.com)





## License

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

See [LICENSE](LICENSE) for full details.

```text
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
```









## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## About

This project is maintained and funded by [Cloud Posse, LLC][website]. Like it? Please let us know by [leaving a testimonial][testimonial]!

[![Cloud Posse][logo]][website]

We're a [DevOps Professional Services][hire] company based in Los Angeles, CA. We ❤️  [Open Source Software][we_love_open_source].

We offer [paid support][commercial_support] on all of our projects.

Check out [our other projects][github], [follow us on twitter][twitter], [apply for a job][jobs], or [hire us][hire] to help with your cloud strategy and implementation.



### Contributors

<!-- markdownlint-disable -->
|  [![Dylan Bannon][dylanbannon_avatar]][dylanbannon_homepage]<br/>[Dylan Bannon][dylanbannon_homepage] |
|---|
<!-- markdownlint-restore -->

  [dylanbannon_homepage]: https://github.com/dylanbannon
  [dylanbannon_avatar]: https://img.cloudposse.com/150x150/https://github.com/dylanbannon.png

[![README Footer][readme_footer_img]][readme_footer_link]
[![Beacon][beacon]][website]

  [logo]: https://cloudposse.com/logo-300x69.svg
  [docs]: https://cpco.io/docs?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=docs
  [website]: https://cpco.io/homepage?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=website
  [github]: https://cpco.io/github?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=github
  [jobs]: https://cpco.io/jobs?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=jobs
  [hire]: https://cpco.io/hire?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=hire
  [slack]: https://cpco.io/slack?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=slack
  [linkedin]: https://cpco.io/linkedin?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=linkedin
  [twitter]: https://cpco.io/twitter?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=twitter
  [testimonial]: https://cpco.io/leave-testimonial?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=testimonial
  [office_hours]: https://cloudposse.com/office-hours?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=office_hours
  [newsletter]: https://cpco.io/newsletter?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=newsletter
  [discourse]: https://ask.sweetops.com/?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=discourse
  [email]: https://cpco.io/email?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=email
  [commercial_support]: https://cpco.io/commercial-support?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=commercial_support
  [we_love_open_source]: https://cpco.io/we-love-open-source?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=we_love_open_source
  [terraform_modules]: https://cpco.io/terraform-modules?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=terraform_modules
  [readme_header_img]: https://cloudposse.com/readme/header/img
  [readme_header_link]: https://cloudposse.com/readme/header/link?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=readme_header_link
  [readme_footer_img]: https://cloudposse.com/readme/footer/img
  [readme_footer_link]: https://cloudposse.com/readme/footer/link?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=readme_footer_link
  [readme_commercial_support_img]: https://cloudposse.com/readme/commercial-support/img
  [readme_commercial_support_link]: https://cloudposse.com/readme/commercial-support/link?utm_source=github&utm_medium=readme&utm_campaign=cloudposse/github-action-validate-codeowners&utm_content=readme_commercial_support_link
  [share_twitter]: https://twitter.com/intent/tweet/?text=GitHub+Action+to+Validate+CODEOWNERS&url=https://github.com/cloudposse/github-action-validate-codeowners
  [share_linkedin]: https://www.linkedin.com/shareArticle?mini=true&title=GitHub+Action+to+Validate+CODEOWNERS&url=https://github.com/cloudposse/github-action-validate-codeowners
  [share_reddit]: https://reddit.com/submit/?url=https://github.com/cloudposse/github-action-validate-codeowners
  [share_facebook]: https://facebook.com/sharer/sharer.php?u=https://github.com/cloudposse/github-action-validate-codeowners
  [share_googleplus]: https://plus.google.com/share?url=https://github.com/cloudposse/github-action-validate-codeowners
  [share_email]: mailto:?subject=GitHub+Action+to+Validate+CODEOWNERS&body=https://github.com/cloudposse/github-action-validate-codeowners
  [beacon]: https://ga-beacon.cloudposse.com/UA-76589703-4/cloudposse/github-action-validate-codeowners?pixel&cs=github&cm=readme&an=github-action-validate-codeowners
