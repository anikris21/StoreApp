# StoreApp

React
- props are passed by reference.
- React element : component combined with props

JSX
- babel/TS compiler for JSX to JS
- 

<h1>
<Sum a = {3} a1 = {4} />
</h1>

JSX compiler
React.createElement(
    'h1',
    null,   //(props)
    React.createElement(
        Sum,
        {a:3, a1:4},
        null
    )
)


React Rules for Hooks
- must be declared at the root of the component


React Events
Assures events operate consistently cross-browser

