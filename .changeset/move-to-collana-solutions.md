---
'@collana-solutions/react-popper': patch
---

The package is now published as `@collana-solutions/react-popper`. The API is
unchanged, and 3.0.1 is available under the new name as well. To migrate,
replace the old package with the new one:

```shell
npm uninstall @neolution-ch/react-popper
npm install @collana-solutions/react-popper
```

Then change the imports:

```js
import { usePopper } from '@collana-solutions/react-popper';
```

`@neolution-ch/react-popper` gets deprecated and receives no further releases.
From this version on, releases carry npm provenance.
