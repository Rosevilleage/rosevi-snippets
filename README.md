# Rosevi Snippets React

A clean, lightweight, and practical collection of **React + TypeScript** snippets designed for everyday frontend development.

---

## Features

- Fast and minimal
- Supports both **TypeScript** and **JavaScript**

---

## Available Snippets

| Prefix | Description                                                      |
| ------ | ---------------------------------------------------------------- |
| `trae` | React arrow function component (TypeScript, with export default) |
| `trfe` | React function component (TypeScript, with export default)       |
| `tra`  | React arrow function component (JS, no export)                   |
| `trf`  | React function component (JS, no export)                         |
| `rae`  | React arrow function component (JS, export default)              |
| `rfe`  | React function component (JS, export default)                    |
| `ust`  | `useState` hook                                                  |
| `ustt` | TypeScript `useState` hook                                       |
| `urf`  | `useRef` hook                                                    |
| `ue`   | `useEffect` hook                                                 |
| `ule`  | `useLayoutEffect` hook                                           |
| `uee`  | `useEffectEvent` hook                                            |
| `fn`   | Regular function                                                 |
| `tfn`  | TypeScript function with return type                             |
| `af`   | Arrow function                                                   |
| `taf`  | TypeScript arrow function with return type                       |

---

## Example Usage

Type the prefix (e.g., `trae`) and press `Tab` → the snippet expands automatically:

```tsx
import React, { ReactElement } from "react";

interface ExampleProps {}

const Example = ({}: ExampleProps): ReactElement => {
  return <div className="Example">Example</div>;
};

export default Example;
```
