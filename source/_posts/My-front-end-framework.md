---
title: My front-end framework
date: 2019-09-19 12:17:23
categories: [Projects, Coding]
tags: [Javascript, front-end, framework]
thumbnail: /images/coding3.jpg
---

Yet another Front end framework with all the main features of the "famous" frameworks, developed only to prove myself that "we can do it". For a demo follow the [link](https://github.com/LorenzoCorbella74/sample-app-for-luce.js) or check the [code](https://github.com/LorenzoCorbella74/vue-fretboard) on Github to see how it works. 


## Main Features
- Components, nested components and multiple istances of the same component
- Components API similar to [Vue.js](https://vuejs.org) with the reactive data model proxied from the ```data``` property and ```Computed properties```
- Component hooks: onInit, onPropsChange, onDestroy
- Two way data binding and data reactivity on primitives, objects and arrays 
- Wrapper of the [fetch API](https://github.com/github/fetch) for HTTP requests
- Client side routing system based on [History API](https://developer.mozilla.org/en-US/docs/Web/API/History), routes with parameters, 
- Filters in template as pure functions
- Props from parent components to child components
- Automatic management of events on the single component instance
- Debug mode (no logging if debug:false...) 
- Event bus: ```.emit()```, ```.on()``` to subscribe and ```.off()``` to unsubscribe to custom events
- Run function during bootstrap to load configurations, service inizialisations etc 

