---
title: 'A new name: enketo'
author: Martijn van de Rijdt
layout: post
permalink: /new-name-enketo
categories:
  - apps
tags:
  - enketo
  - survey
---
Finally, I have come up with a better name for the offline-capable-and-open-source-form-format-using [survey application][1] with less scope for confusion. Rapaide has now been renamed to: **enketo**

 [1]: /enkets-new-architecture/ "Enketo’s New Architecture"

“enketo” is Esperanto for survey and matches well with the wide user potential the application has (beyond aid workers).

[![enketo screenshot][2]][3]

 [2]: ../files/2012/08/elephantdeath-300x228.png
 [3]: http://enketo.org

More updates:

*   JavaRosa engine is working well and supports repeats (fully), translations (all), constraints, branching, triggers, outputs, defaults, media labels (hosted on Aggregate) and appearances (partial).
*   The focus in August will be on the data entry component (local storage of data and offline launch). Also, the source code for the fork of the excellent [javascript XPath evaluator][3] (to which I’ve just added the custom JavaRosa functions and accompanying tests) will be made available on GitHub.
*   September will be mostly dedicated to finalizing support for the newer parts of the JavaRosa spec (e.g. [cascading selections][4]) and creating a huge quantity of additional automated tests.
*   October: widgets…. and then in November the alpha launch(?)

 [3]: http://www.pokret.org/products/xpathjs-javascript-based-xpath-library/ "Link to developer of XPathJS"
 [4]: http://opendatakit.org/help/form-design/cascading-selects/ "Technical article about the new cascading selects in ODK"