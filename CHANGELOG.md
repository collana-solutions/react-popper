# @collana-solutions/react-popper

## 3.0.2

### Patch Changes

- [#12](https://github.com/collana-solutions/react-popper/pull/12)
  [`0342680`](https://github.com/collana-solutions/react-popper/commit/034268086b4c87c0759536a4c7a9c16dbb449b2f)
  Thanks [@neotrow](https://github.com/neotrow)! - The package is now published
  as `@collana-solutions/react-popper`. The API is unchanged, and 3.0.1 is
  available under the new name as well. To migrate, replace the old package with
  the new one:

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

## [3.0.1] - 2026-02-23

### Added

- Support for React 19

[3.0.1]: https://github.com/neolution-ch/react-popper/compare/3.0.1-rc.0...3.0.1
