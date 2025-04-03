# React-Js-Notes

## 1. **React Hooks (Commonly Used)**  -> simplify state management & side effects in functional components!

✅ **1. `useState()`** → Manages component state.  
```jsx
const [count, setCount] = useState(0);
setCount(count + 1);
```

✅ **2. `useEffect()`** → Runs side effects (API calls, event listeners).  
```jsx
useEffect(() => { console.log("Component mounted"); }, []);
```
