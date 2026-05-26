# Lab8-Starter

Name(s): Han Yang-Lin

Pages: [index.html](https://hyanglin0.github.io/CSE110Lab8/)

Graceful Degradation and Service Workers: Graceful degradation is the design principle to ensure that basic functionalities still work even when some technologies fail, rather than collapsing entirely. Service workers are an example of graceful degradation in practice. When the network connection is fast and working, the app can fetch resources through network requests and the service workers will save them to a cache. So in a situation where the user is offline or the network connection is slow, the service workers can intercept those network requests and return data stored in the cache so the app still works.

![PWA Screenshot](./pwa.jpg)