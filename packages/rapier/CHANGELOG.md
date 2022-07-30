# @threlte/extras

## 0.0.2

### Patch Changes

- 62d2c5c: fixed `<RigidBody>` initial transforms

## 0.0.1

### Patch Changes

- 7a3fa6b: # NEW PACKAGE: @threlte/rapier

  This package provides easy to use components and hooks to use the [rapier](https://rapier.rs/) physics engine in threlte.

  It comes with several components to get you started: [`<World>`](https://threlte.xyz/rapier/world), [`<RigidBody>`](https://threlte.xyz/rapier/rigid-body), [`<Collider>`](https://threlte.xyz/rapier/collider), [`<AutoColliders>`](https://threlte.xyz/rapier/auto-colliders), [`<CollisionGroups>`](https://threlte.xyz/rapier/collision-groups) and [`<Debug>`](https://threlte.xyz/rapier/debug).

  It also features several handy hooks: [`<useRapier>`](https://threlte.xyz/rapier/use-rapier), [`<useCollisionGroups>`](https://threlte.xyz/rapier/use-collision-groups) and [`<useRigidBody>`](https://threlte.xyz/rapier/use-rigid-body).

## 4.0.0

### Major Changes

- 52e021c: # Breaking Change

  The threlte repository has been moved to its own GitHub Organization: [https://github.com/threlte/threlte](https://github.com/threlte/threlte).
  threlte consists now of two npm packages: `@threlte/core` and `@threlte/extras`, managed in a mono repository:

  `@threlte/core` consists of components, hooks and other utilites that follow three.js principles, nomenclature and inheritance as closely as useful and possible. Therefore components that have been part of the package `threlte` have been moved to the new home of all kinds of useful abstractons: `@threlte/extras`.

  `@threlte/extras` consists of useful abstractions and helpers that you may find yourself use all the time. These components do not need to follow three.js principles as strict as exports from `@threlte/core`, but they do where it makes sense.

  ## The breaking changes in detail:

  - Moved `<GLTF>` component as well as `useGltf` hook to `@threlte/extras`.
  - Moved `<Text>` component to `@threlte/extras`.

  ## How to update

  Replace imports from `threlte` and `threlte/extras`:

  1. `npm rm threlte`
  2. `npm i -D @threlte/core @threlte/extras`
  3. Replace `import {…} from 'threlte'` with `import {…} from '@threlte/core'`
  4. Replace `import {…} from 'threlte/extras'` with `import {…} from '@threlte/extras'`

  Specifically replace imports of `<GLTF>`, `useGltf` or `<Text>`:

  3. Replace `import { GLTF, useGltf, Text } from 'threlte'` with `import { GLTF, useGltf, Text } from '@threlte/extras'`

  # Other changes

  - The documentation is now hosted on Vercel and as such we are hoping for a Vercel Sponsorship for OSS. There have also been some style fixes and overhauls.

## 3.13.10

### Patch Changes

- 4de7371: added svelte identifier

## 3.13.9

### Patch Changes

- 41cc5a1: test

## 3.13.8

### Patch Changes

- 79a64f5: test

## 3.13.7

### Patch Changes

- test

## 3.13.6

### Patch Changes

- trying to delete

## 3.13.5

### Patch Changes

- 11aa5eb: yes

## 3.13.4

### Patch Changes

- 0c40456: added scripts to clean up packages
- 7cc4e5d: added node types

## 3.13.3

### Patch Changes

- a2a6d93: test

## 3.13.2

### Patch Changes

- 8dbf8cd: Test