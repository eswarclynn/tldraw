# Changelog

## 1.7.0

### Minor Changes

- Update dependencies and monorepo.

### Patch Changes

- Updated dependencies
  - @tldraw/intersect@1.7.0
  - @tldraw/vec@1.7.0

## 1.5.0

- Fix propagation on pointer move events.

## 1.4.3

- Update README
- Update LICENSE year

## 1.4.0

- Adds support for performance modes.
- Makes assets an optional prop for the Renderer.

## 1.3.0

- Adds assets for image and video shape types.

## 1.2.10

- Fix bug in shape events.

## 1.2.9

- Improves multiplayer cursor appearance.

## 1.2.2

- Adds mobx and support for mobx observables in the Renderer's props.
- Removes unused code.

## 0.1.21

New:

- Adds the `isGhost` prop to `TLShape`. In `TLComponentProps`, the `isGhost` prop will be true if either a shape has its `isGhost` set to `true` OR if a shape is the descendant of a shape with `isGhost` set to `true`. A ghost shape will have the `tl-ghost` class name, though this is not used in the Renderer. You can set it yourself in your app.
- Adds the `isChildOfSelected` prop for `TLComponentProps`. If a shape is the child of a selected shape, its `isChildOfSelected` prop will be true.

Improved:

- Fixes a bug that could occur with the order of grouped shapes.
- Adds an Eraser tool to the advanced example.
- Adds a Pencil tool to the advanced example.

## 0.1.20

- Update docs.
- Adds `hideResizeHandles` prop.

## 0.1.19

- Remove stray `index.js` files.

## 0.1.18

- Even more dependency fixes.

## 0.1.17

- More dependency fixes.

## 0.1.16

- Fix dependencies, remove `@use-gesture/react` from bundle.

## 0.1.15

- Fix README.

## 0.1.14

- Add README to package.

## 0.1.13

- Remove `type` from `TLBinding`.

## 0.1.12

- Fix bug with initial bounds.

## 0.1.12

- Fix bug with initial bounds.

## 0.1.12

- Fix bug with bounds handle events.

## 0.1.11

- Fix bug with initial camera state.

## 0.1.10

- Improve example.
- Improve types for `TLPage`.

## 0.1.9

- Bug fixes.

## 0.1.8

- Expands README.
- Removes properties specific to the tldraw app.

## 0.1.7

- Fixes selection bug with SVGContainer.
- Removes various properties specific to the tldraw app.

## 0.1.0

- Re-writes API for ShapeUtils.
