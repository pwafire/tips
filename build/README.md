### [ Building Your Progressive Web App ](https://pwafire.org/developer/pwa/started/)

You only need two files; 

    - A Service Worker
    
    - An App Manifest
    
   > **tip 1; for service worker**
   
   For **static (pwa) sites** you could just add a [simple service worker like this](https://pwafire.org/developer/pwa/started/#sw-config) and for a more **dynamic pwa** then [workbox library](https://developers.google.com/web/tools/workbox/) fits that perfectly, [check out an example here](https://pwafire.org/developer/pwa/started/#workbox-service-worker)
   
   > **tip 2; for app manifest**
   
   To have your web app even much more easily installable in all the browsers platforms, there is a new more better and meaningful manifest naming standard; name your **manifest** like, [app.webmanifest](https://github.com/mayeedwin/pwafire/blob/master/bundle/default/app.webmanifest)
   
   > **tip 3; add background sync**
   
   Service Workers solve the page loading part by letting you serve content from a cache. But what about when the page needs to send something to the server? [Learn how to do so here](https://pwafire.org/developer/docs/background-sync/)
