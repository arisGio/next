# next

Studying NextJS from the official documentation

## from js to react migration

- dom of page differs from source code in browser dev tools
- html reps initial page content
- BUT DOM reps UPDATED PAGE CONTENT changed by JS

## jsx

- js xml
- 3 rules
- return single root element
- close all the tags
- camelCase most of the things

## babel

- type=text/jsx
- inform babel what code to transform

## imperative vs declarative

- comparing previous js with current react code difference is huge
- do not forget the essence here regarding DOM and source code
- relevant for SSR later on

## components

- should be capitalized
- use angle brackets < >

## props vs state

- props are passed to components as the first function parameter
- state is initiated and stored within a component
- you can pass the state information to children components as props
- but logic for updating the state should be kept within the component where state was initially created

# from react to nextjs migration

- create package.json with empty json inside
- npm install react react-dom next
- create .gitignore on your own to avoid commiting the unwanted files
- NOTE: already we see that we need to configure things on our own
- in the future all this will be automatically setup and configured using the nextjs tooling

## run next dev server

- npm run dev
- fast refresh -> ENJOY AS ALWAYS
- comparing we see a reduction in lines of code
- react is a library that provides essential primitives for building modern interactive UI
- still work to involved to combine that UI you create into an application
- we removed babel and some other tooling configuration, not to be bothered with it from now on
- already the developer experience is mucho better
