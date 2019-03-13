---
id: config
title: config
---
## الإسم
git-config :

## مُلخّص

<!--DOCUSAURUS_CODE_TABS-->
<!--الأمر-->
```bash
git config [<file-option>] [--type=<type>] [--show-origin] [-z|--null] name [value [value_regex]]
git config [<file-option>] [--type=<type>] --add name value
git config [<file-option>] [--type=<type>] --replace-all name value [value_regex]
git config [<file-option>] [--type=<type>] [--show-origin] [-z|--null] --get name [value_regex]
git config [<file-option>] [--type=<type>] [--show-origin] [-z|--null] --get-all name [value_regex]
git config [<file-option>] [--type=<type>] [--show-origin] [-z|--null] [--name-only] --get-regexp name_regex [value_regex]
git config [<file-option>] [--type=<type>] [-z|--null] --get-urlmatch name URL
git config [<file-option>] --unset name [value_regex]
git config [<file-option>] --unset-all name [value_regex]
git config [<file-option>] --rename-section old_name new_name
git config [<file-option>] --remove-section name
git config [<file-option>] [--show-origin] [-z|--null] [--name-only] -l | --list
git config [<file-option>] --get-color name [default]
git config [<file-option>] --get-colorbool name [stdout-is-tty]
git config [<file-option>] -e | --edit
```
<!--END_DOCUSAURUS_CODE_TABS-->

## التفاصيل

## الخيارات