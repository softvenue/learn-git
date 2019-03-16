---
id: format-patch
title: format-patch
---

## الإسم
git-format-patch : 

## مُلخّص

<!--DOCUSAURUS_CODE_TABS-->
<!--الأمر-->
```bash
git format-patch [-k] [(-o|--output-directory) <dir> | --stdout]
		   [--no-thread | --thread[=<style>]]
		   [(--attach|--inline)[=<boundary>] | --no-attach]
		   [-s | --signoff]
		   [--signature=<signature> | --no-signature]
		   [--signature-file=<file>]
		   [-n | --numbered | -N | --no-numbered]
		   [--start-number <n>] [--numbered-files]
		   [--in-reply-to=Message-Id] [--suffix=.<sfx>]
		   [--ignore-if-in-upstream]
		   [--rfc] [--subject-prefix=Subject-Prefix]
		   [(--reroll-count|-v) <n>]
		   [--to=<email>] [--cc=<email>]
		   [--[no-]cover-letter] [--quiet] [--notes[=<ref>]]
		   [--interdiff=<previous>]
		   [--range-diff=<previous> [--creation-factor=<percent>]]
		   [--progress]
		   [<common diff options>]
		   [ <since> | <revision range> ]
```
<!--END_DOCUSAURUS_CODE_TABS-->

## التفاصيل

## الخيارات

