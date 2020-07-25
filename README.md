# Vue.js Starter Pack

It's an example-repository, the output of `vue create something`. 

## Vue CLI

To install the new package, use one of the following commands. 
You need administrator privileges to execute these (`$ sudo something`, if you are on Linux-based operating system).

```bash
npm install -g @vue/cli
```

You can check you have the right version with this command:

```bash
vue --version
```

__Upgrading__ \
To upgrade the global Vue CLI package, you need to run:

```bash
npm update -g @vue/cli
```

## Create a new Project

```bash
vue create hello-world
```
where _hello-world_ is the name of your new project.

The default setup is great for quickly prototyping a new project, while the manual setup provides more options that are likely needed for more production-oriented projects.

__Vue UI__ \
You can also create and manage projects using a graphical interface with the vue ui command:

```bash 
vue ui
```

## Install from existing repo

```npm install```

__then:__

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
