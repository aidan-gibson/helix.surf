# overview

uses threejs, sweetalert, vite->netlify->helix.surf


# building / testing
for testing, `npx vite --host` (host part so it's exposed so others on my net)
`npx vite build` outputs to dist/ for actual deployment





# todo

loading assets bar/circle thingy (music AND 3d objs)
would be cool if favicon animated (swapping strand colors)
actually test VR

hovering over link gives iframe 



  * typescript
  * go thru three.js docs, learn it all (it's finite) redo things as i go

* de-oop / general cleanup
  * keeping resizer.js modularized fs, makes sense
  * Loop.js is on thin ice but I don't care enough to fuck w it rn


* cookie to remember the init start open popup (dies in 5 min or smth short)
* About link
* optimize vite?

DNA select could b prettier


assets loading bar

# logistical



use vite, not webpack
`vite.config.ts`
`vite-plugin-ssr`

`npm run dev` to do locally
`npm run build`


`tsconfig.json`
`tsconfig.node.json`


replace datgui with tweakpane
`npm install --save tweakpane`
Additional type definitions for development in TypeScript
`npm install --save-dev @tweakpane/core`
import {Pane} from 'tweakpane';
const pane = new Pane();
https://tweakpane.github.io/docs/quick-tour/