# @roadiehq/backstage-plugin-argo-cd

## 2.2.5

### Patch Changes

- b619d5d8: make `getBaseUrl` and `fetchDecode` methods public so that they can be used when the plugin is subclassed

## 2.2.4

### Patch Changes

- 6d186f0f: Bump plugin's version to backstage version 1.10.1

## 2.2.3

### Patch Changes

- 054d585b: Bump plugin versions to be compatible by backstage 1.9.1

## 2.2.2

### Patch Changes

- 7084d814: Bump plugins version to backstage 1.8.3

## 2.2.1

### Patch Changes

- b7a7536a: Fix circular dependencies.

## 2.2.0

### Minor Changes

- 015aebdf: Bump plugins version to be compatible by backstage 1.7

## 2.1.10

### Patch Changes

- 6daac9bc: Encoded all usage of app names and selectors

## 2.1.9

### Patch Changes

- eaa0bb2: update dependencies

## 2.1.8

### Patch Changes

- 99153fe: Move react-router and react-router-dom dependencies to peerDependencies because of the migration to the stabel version of react-router in backstage/backstage. See the migration guide [here](https://backstage.io/docs/tutorials/react-router-stable-migration#for-plugin-authors)

## 2.1.7

### Patch Changes

- 151b46b: bump to latest backstage package versions

## 2.1.6

### Patch Changes

- c9cfaad: Release all plugins after fixing typescript exports issue.

## 2.1.5

### Patch Changes

- 86eca6a: Update dependencies

## 2.1.4

### Patch Changes

- e92dc3b: properly escaped app selectors

## 2.1.3

### Patch Changes

- 9db0101: Hide instance column in argo cards when using a single argo instance

## 2.1.2

### Patch Changes

- 6b4cc16: Update dependencies
  Add package information to the package.jsons, to tell the backstage cli how to run the tests

## 2.1.1

### Patch Changes

- ae873be: Fix Argo CD Dashboard button

## 2.1.0

### Minor Changes

- 0af1e28: add additional information from argo cd in a drawer component

## 2.0.0

### Major Changes

- df841f0: Update dependecies to follow latest upstream version. Removed deprecated props of type 'Entity' passed into components as it is grabbed from context instead.

## 1.6.0

### Minor Changes

- f0421b4: Bumped to the latest upstream packages versions

## 1.5.14

### Patch Changes

- 5a2757c: Change notice headers to contain Larder Software Limited

## 1.5.13

### Patch Changes

- f5cd7e4: Update dependencies to latest Backstage packages

## 1.5.12

### Patch Changes

- 46b19a3: Update dependencies

## 1.5.11

### Patch Changes

- c779d9e: Update dependencies

## 1.5.10

### Patch Changes

- 7da7bfe: Update dependencies

## 1.5.9

### Patch Changes

- f79f2a7: Gracefully handle situation where an app is missing operationState

## 1.5.8

### Patch Changes

- 5ae1b4b: Update README.md files

## 1.5.7

### Patch Changes

- b5db653: Update dependecies to latest packages

## 1.5.6

### Patch Changes

- a02dbf5: Migrating to TestApiProvider in the tests

## 1.5.5

### Patch Changes

- 142ce1c: Moved React dependencies to `peerDependencies` and allow both React v16 and v17 to be used.

## 1.5.4

### Patch Changes

- ecd06f5: Make "@backstage/core-app-api" a dev dependency

## 1.5.3

### Patch Changes

- b69543e: Fix bug where an instance with no items would crash the card

## 1.5.2

### Patch Changes

- 49abec7: Update patch to release new changes.

## 1.5.1

### Patch Changes

- a728fd1: Update underlying packages and release.

## 1.5.0

### Minor Changes

- ed90f25: Breaking dependency updates for @backstage/core-app-api, @backstage/test-utils, @backstage/core-plugin-api, @backstage/backend-common && @backstage/integration

## 1.4.0

### Minor Changes

- 1d256c6: Support multiple Argo instances using the app-selector annotation

## 1.3.3

### Patch Changes

- 120ca2e: Removed deprecated `description` option from `ApiRefConfig` for all plugins

## 1.3.2

### Patch Changes

- 4d426f9: Updated dependencies to follow latest Backstage release

## 1.3.1

### Patch Changes

- 3f280ef: Updated 'msw' package version in order to correctly run tests.
