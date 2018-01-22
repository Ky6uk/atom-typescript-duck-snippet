Atom Duck snippet for React/Redux and TypeScript
================================================

The [Duck](https://github.com/erikras/ducks-modular-redux) snippet for React/Redux. This snippet uses TypeScript syntax.

The Snippet
-----------

| Trigger   | Content |
| :-------: | ------- |
| `duck`    | the snippet |

Generated Code
--------------

```ts
interface Action {
  readonly type?: string;
}

const defaultState = {};

// Actions
const ACTION = 'duck-name/ACTION';

// Reducer
export default function reducer(state = defaultState, action: Action = {}) {
  switch (action.type) {
    case ACTION: {
      return state;
    }

    default: {
      return state;
    }
  }
}

// Action Creators

export function actionCreator() {
  return { type: ACTION };
}

```

License
-------

MIT License © Roman Nuritdinov (Ky6uk)
