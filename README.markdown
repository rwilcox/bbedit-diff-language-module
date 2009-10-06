Introduction To This Project
=============================

This is a BBEdit Codeless Language Module that provides good highlighting for viewing diffs (files with a .diff extension) in BBEdit.

NOTE: This module currently only supports what I call CVS style diffs, AKA diffs of the style:

  `< Change that is moving OUT of the file`  
  `> Change that is moving INTO the file`

Sadly, the world of source control has moved to unified diffs, diffs of the style:

`- Change that is moving out of the file`  
`+ Change that is moving INTO the file`  

This module tries hard to keep good visual appearance, maybe at the sake of semantics. For example, a removed line is tagged as a comment line in BBEdit, because in my/the standard color scheme, that means said line gets a gray-ish color.


Installation
=============================

Copy diff.plist into ~/Library/Application Support/BBEdit/Language Modules/). If no such folder exists, you may create one. After installing a new language module, you will need to quit and relaunch BBEdit in 
order to use it.

Areas For Improvement
===========================

  * Supporting Unified Diffs
  * Using new features of codeless language modules since 2005 (aka: BBEdit 7 or in whatever version codeless language modules came out in