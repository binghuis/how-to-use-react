# 如何使用 React

本项目按照 React 18 最新文档结合代码探索各个 Hook 、API 和 组件的实践。

---

`use`

[读取 context](./app/use-w-context/page.tsx)

[读取 Promise](./app/use-w-promise/page.tsx)

[将数据从服务器流式传递给客户端](./app/use-w-stream/page.tsx)

`useContext`

[读取 context](./app/use-context/page.tsx)

`useReducer`

[整合状态更新逻辑](./app/use-reducer/page.tsx)

---

`useState` & `flushSync`

[状态管理、异步批处理、同步更新、用 key 初始化 state、用 use-immer 优化对象/数组更新](./app/use-state/page.tsx)

`useMemo`

[值记忆化](./app/use-memo/page.tsx)

`useCallback`

[函数记忆化](./app/use-callback/page.tsx)

`memo`

[组件记忆化](./app/memo/page.tsx)

`useDeferredValue`

[UI 延迟更新](./app/use-deferred-value/page.tsx)

---

`useEffect` & `useLayoutEffect`

[副作用处理]('./app/use-effect/page.tsx')

`useEffectEvent`

`useSyncExternalStore`

---

`useRef`

`useImperativeHandle`

`forwardRef`

---

<details>
<summary>
<b>什么时候用 `memo`、`useMemo` 和 `useCallback`、`useDeferredValue`</b>
</summary>
<img src='./app/assets/when-to-use-memo.png' />
</details>
