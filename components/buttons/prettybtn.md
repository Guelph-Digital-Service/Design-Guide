---
layout: component-detail
group: components
subgroup: buttons
permalink: /components/buttons/prettybtn

title: Pretty Button
description: " A 'pretty' buttons using guelph.ca styles, allows for different prefix icons using classes to identify button usages. A 'Pretty Button' should only be used on links (`<a>`) that require some extra flare. These include for example: links which direct the user to 'learn more', 'provide feeedback' or 'apply' "
status: Complete

variations:
- title: Pretty Button - Default
  description: A standard button using guelph.ca styles
  styleModifier: prettybtn
  includeCat: prettybtn

- title: Pretty Button - View
  description: A button defining a link that the user will 'view'
  styleModifier: prettybtn link-view
  includeCat: prettybtn
  includeSubCat: view

- title: Pretty Button - Feedback
  description: A button defining a link that the user will use to provide 'feedback'
  styleModifier: prettybtn link-feedback
  includeCat: prettybtn
  includeSubCat: feedback

- title: Pretty Button - Help
  description: A button defining a link that the user will use to get 'help'
  styleModifier: prettybtn link-help
  includeCat: prettybtn
  includeSubCat: help

- title: Pretty Button - Learn
  description: A button defining a link that the user will use to 'learn'
  styleModifier: prettybtn link-learn
  includeCat: prettybtn
  includeSubCat: learn

- title: Pretty Button - Report
  description: A button defining a link that the user will use to make a 'report'
  styleModifier: prettybtn link-report
  includeCat: prettybtn
  includeSubCat: report

- title: Pretty Button - Pay
  description: A button defining a link that the user will use to make a 'payment'
  styleModifier: prettybtn link-pay
  includeCat: prettybtn
  includeSubCat: pay

classes:
- className: prettybtn
  description: Apply to an `<a>` tag that you would like to become a pretty button. This will attach the baseline styles.
- className: link-view
  description: Add to the `prettybtn` element to add 'view' icon.
- className: link-report
  description: Add to the `prettybtn` element to add 'report' icon.
- className: link-pay
  description: Add to the `prettybtn` element to add 'pay' icon.
- className: link-learn
  description: Add to the `prettybtn` element to add 'learn' icon.
- className: link-help
  description: Add to the `prettybtn` element to add 'help' icon.
- className: link-feedback
  description: Add to the `prettybtn` element to add 'feedback' icon.

fine-print:
- version: 0.3
  update: May 13, 2021

---
