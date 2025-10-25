# Rosevi Snippets React

React + TypeScript 개발을 위한 가볍고 실용적인 스니펫 모음입니다.
자주 사용하는 컴포넌트 및 훅 패턴을 빠르게 입력할 수 있습니다.

## 주요 특징

빠르고 간결한 코드 자동 완성

TypeScript와 JavaScript 모두 지원

## 사용 가능한 스니펫

| Prefix | Description                                                  |
| ------ | ------------------------------------------------------------ |
| `trae` | React 화살표 함수 컴포넌트 (TypeScript, export default 포함) |
| `trfe` | React 일반 함수 컴포넌트 (TypeScript, export default 포함)   |
| `tra`  | React 화살표 함수 컴포넌트 (JavaScript, export 없음)         |
| `trf`  | React 일반 함수 컴포넌트 (JavaScript, export 없음)           |
| `rae`  | React 화살표 함수 컴포넌트 (JavaScript, export default 포함) |
| `rfe`  | React 일반 함수 컴포넌트 (JavaScript, export default 포함)   |
| `ust`  | `useState` hook                                              |
| `ustt` | TypeScript `useState` hook                                   |
| `urf`  | `useRef` hook                                                |
| `ue`   | `useEffect` hook                                             |
| `ule`  | `useLayoutEffect` hook                                       |
| `uee`  | `useEffectEvent` hook                                        |
| `fn`   | 일반 함수                                                    |
| `tfn`  | 반환 타입을 지정한 TypeScript 함수                           |
| `af`   | 화살표 함수                                                  |
| `taf`  | 반환 타입이 포함된 TypeScript 화살표 함수                    |

## 사용 예시

예: trae 입력 후 Tab → 자동 완성됩니다.

```tsx
import React, { ReactElement } from "react";

interface ExampleProps {}

const Example = ({}: ExampleProps): ReactElement => {
  return <div className="Example">Example</div>;
};

export default Example;
```

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
