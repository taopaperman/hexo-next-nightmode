# Hexo NexT Night Mode

![Theme Version](https://img.shields.io/badge/NexT-v7.3.0+-blue.svg?style=flat-square)
![Package Version](https://img.shields.io/github/package-json/v/1v9/hexo-next-nightmode?style=flat-square)

Add Night Mode support for NexT.

> Try scheme Mist for now, since nightmode.styl lacks much...

## Install

> This plugin has been [released](https://github.com/1v9/hexo-next-nightmode/packages/26527) to [GitHub Package Registry](https://github.com/features/package-registry) and you can choose one of the following ways to install it.

### Default

```bash
npm i 1v9/hexo-next-nightmode
```

If the above installation failed, please try:

```bash
npm i 1v9/hexo-next-nightmode#master
```

### Via Github

```bash
npm i https://github.com/1v9/hexo-next-nightmode
```

### Via GitHub Package Registry (Not Recommended)

> You need to configure authToken for GPR by yourself

```bash
npm config set @1v9:registry=https://npm.pkg.github.com
npm i @1v9/hexo-next-nightmode
```

## Uninstall

```bash
npm un @1v9/hexo-next-nightmode
```

## Configure

You can add follow options in both **hexo** or **theme** `_config.yml`.

```yml
next_nightmode:
  enable: false
  # FontAwesome or ForkAwesome icon in sidebar button
  icon: lightbulb-o
  # Text for sidebar button
  text: Night Mode
  # If ture, when you disable Night Mode, Hexo will show warning messages in your console.
  reminder: false
```

## Custom

NexT supports customizing styles, so you can custom dark mode style by yourself, check `nightmode.styl` then do your job.
