PSStyleGuide
============

The Unofficial PowerShell Style Guide

NOTE: Markdown documents on GitHub support linking to any header, so when editing, please observe the following conventions:

1. Keep rules within the section where they make sense.
2. Sections should be headers level 3 (have three hashes): `### Naming Conventions`
3. Rules should be header level 6 (have six hashes): `###### Linkable Rule`
4. Rules should have an explanatory paragraph
5. Rules should have examples and counter examples
6. When possible, phrase the rule name as the positive, rather than the negative.
  * Don't say: "Avoid using aliases"
  * Do say: "Use full command names"

7. When you do write a rules that people should "avoid" certain behavior, you should always start with "avoid" and end with an "Instead" sentence, like:
   > ###### Avoid using aliases. 
   > Every PowerShell scripter has to learn the full command names, but different people learn and use different aliases, so please avoid leaving them in shared code. *Instead*, use the more universally known full command name.

