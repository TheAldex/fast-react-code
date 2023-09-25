# Fast React Code

## React Code Snippets Extension for VIsual Studio Code

An extension for Visual Studio Code which includes a collection of snippets to use while coding with React (https://react.dev/learn).

## Installation and Usage

In order to install an extension you need to launch the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

As VS Code from version 0.10.10 supports React components syntax inside js files the snippets are available for JavaScript language as well.
In the following example you can see the usage of a React stateless component with prop types snippets inside a js and not jsx file.

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

## Features

The different snippets, their use and their trigger within the editor are described below. The **⇥** means the `TAB` key (or, alternatively, `ENTER` key).

### React Hooks

|  Trigger | Content                                                          |
| -------: | ---------------------------------------------------------------- |
|   `!us→` | useState Hook Template                                           |
|   `!ue→` | useEffect Hook Template                                          |
|   `!uc→` | useContext Hook Template                                         |
|   `!ur→` | uuseReducer Hook Template                                        |
|   `!ucall→` | useCallback Hook Template                                     |
|   `!um→` | useMemo Hook Template                                            |
|   `!uref→` | useRef Hook Template                                           |
|   `!uimp→` | useImperativeHandle Hook Template                              |
|   `!ulay→` | useLayoutEffect Hook Template                                  |
|   `!udeb→` | useDebugValue Hook Template                                    |
|   `!udef→` | useDeferredValue Hook Template                                 |
|   `!ut→` | useTransition Hook Template                                      |
|   `!uid→` | useId Hook Template                                             |
|   `!usync→` | useSyncExternalStore Hook Template                            |
|   `!uins→` | suseInsertionEffect Hook Template                              |

### React Components Skeletons

|  Trigger | Content                                                          |
| -------: | ---------------------------------------------------------------- |
|   `!impr→` | import React statement                                         |
|   `!impf→` | import function statement                                      |
|   `!inc→` | includo file                                                    |
|   `!exp→` | export default                                                  |
|   `!expc→` | export const                                                   |
|   `!cc→` | component const class template                                   |
|   `!ccl→` | component class template                                        |
|   `!cf→` | component function template                                      |

