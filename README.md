# ms-teams-orb

CircleCI Orb to handle Microsoft Teams notifications

This orb is based on the https://github.com/cloudradar-monitoring/circleci-orbs implementation.

It was customized to provide different default values for the typical use case, fix some message template bugs, and also improve the message layout.

If new to CircleCI orb creation the [Manual Orb Authoring Process](https://circleci.com/docs/2.0/orb-author-validate-publish/) is much easier to follow for simple orbs like this. See the [Publishing Orbs](https://circleci.com/docs/2.0/creating-orbs/) page for versioning details. The full-blown [Orb Authoring Process](https://circleci.com/docs/2.0/orb-author/) is the CircleCI recommended method but I found it too complex for any simple orb work I was doing.
