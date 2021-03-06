
## Getting Started

```
git clone 
npm install
```

## Deployment

1. `npm publish`
### npm

```
import adafel from 'adafel';
import 'adafel/build/index.css' // If you import a css file in your library

let libraryInstance = new adafel();
...
```

### self-host/cdn

```
<link href="build/index.css" rel="stylesheet">
<script src="build/index.js"></script>

let MyLibrary = window.MyLibrary.default;
let libraryInstance = new MyLibrary();
...
```
