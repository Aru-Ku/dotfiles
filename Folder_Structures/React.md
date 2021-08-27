## React

```bash
app-name
  ├── node_modules
  ├── build
  ├── src
  :   ├── components # FOR GLOBAL COMPONENTS
  :   ├── <pages/containers>
  :   :   ├── <page-name/container-name>
  :   :   :   ├── components
  :   :   :   :   └── <component-name>
  :   :   :   :       ├── styles.[css, scss, sass, less, js]
  :   :   :   :       └── index.[js, jsx, tsx]
  :   :   :   ├── styles.[css, scss, sass, less, js]
  :   :   :   └── index.[js, jsx, tsx]
  :   :   └── index.[js, jsx, tsx]
  :   ├── styles
  :   :   ├── styles.[css, scss, sass, less, js]
  :   :   └── theme.[css, scss, sass, less, js]
  :   ├── utils
  :   :   ├── <util-name>.[js, ts]
  :   :   └── index.[js, ts]
  :   ├── <types/modals>
  :   ├── lib
  :   :   ├── <scrips/lib/apis>.[json, js]
  :   :   └── index.[js, ts]
  :   ├── App.[js, jsx, tsx]
  :   ├── reportWebVitals.js
  :   ├── service-worker.js
  :   └── index.[js, jsx, tsx]
  ├── public
  :   ├── fonts
  :   :   └── <font-names>
  :   :       └── <font-name>.[ttf, woff, otf, woff2]
  :   ├── images
  :   :   └── <static-image-name>.[png, jpeg, jpg, gif, svg, webp]
  :   ├── favicon.ico
  :   ├── index.html
  :   ├── logo192.png
  :   ├── logo512.png
  :   ├── manifest.json
  :   ├── sitemap.xml
  :   └── robots.txt
  ├── README.md
  ├── package.json
  ├── package-lock.json OR yarn.lock
  └── .gitignore
```
