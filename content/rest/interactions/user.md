---
title: User interactions
shortTitle: User
allowTitleToDifferFromFilename: true
intro: 'Use the REST API to temporarily restrict which type of user can comment, open issues, or create pull requests in your public repositories.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
autogenerated: true
---

## About user interactions

You can use the REST API to temporarily restrict which type of user can comment, open issues, or create pull requests on your public repositories. {% data reusables.interactions.interactions-detail %} Here's more about the types of {% data variables.product.product_name %} users:

* {% data reusables.interactions.existing-user-limit-definition %} from interacting with your repositories.
* {% data reusables.interactions.contributor-user-limit-definition %} from interacting with your repositories.
* {% data reusables.interactions.collaborator-user-limit-definition %} from interacting with your repositories.

Setting the interaction limit at the user level will overwrite any interaction limits that are set for individual repositories owned by the user. To set different interaction limits for individual repositories owned by the user, use the [Repository](#repository) interactions endpoints instead.


<!-- Content after this section is automatically generated -->
