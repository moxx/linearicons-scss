# linearicons-scss
 Scss version of linearicons Font Icons, ready to drop right into your Scss projects
 
Use in sass/scss

```sass
@import 'path/to/my/components/linearicons-scss/src/scss/linearicons'
```

Use as css (located in dist/css)
```html
<link href="/path/to/my/css/linearicons.min.css" rel="stylesheet">
```

Example Html
```html
<h1><i class="lineico-home"></i> Home</h1>
```

With this package we ship also the possibility to rename the css-prefix (located in /src/scss/_variables.scss);

#Installation
Copy your extracted Linearicons folder into the `src` folder.
```
src/Linearicons/
    ├── EPS
    ├── Font
    │   └── demo-files
    ├── PNG
    │   ├── 20px
    │   ├── 40px
    │   ├── 60px
    │   └── 80px
    └── SVG
```
Required are the Folders `Linearicons` and `Linearicons\Font` including the demo-files.

After you copied the Folder, just run:
```bash
npm install
gulp
```

This will end generate all you need. For details watch the gulpfile.js
