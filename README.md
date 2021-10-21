# context-typescript-template


```
import {
  createContext,
  ReactNode,
  useContext,
  useEffect,
  useState,
} from "react";

type CategoryContextData = {
 
};

type CategoryProviderProps = {
  children: ReactNode;
};

const CategoryContext = createContext({} as CategoryContextData);

export function CategoryProvider({ children }:CategoryProviderProps) {
  
  return (
    <CategoryContext.Provider value={{}}>
      {children}
    </CategoryContext.Provider>
  );
}

export const useCategory = () => useContext(CategoryContext);

```
