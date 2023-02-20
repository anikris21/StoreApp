# StoreApp

React
- props are passed by reference.
- React element : component combined with props
- props - pass data into components
- React components arranged as hierarchy/DAG
    -  data is passed through nested components through props
    - data is passed out of the components through function passed as prop.  
 updating data :
    - props
    - hooks


JSX
- babel/TS compiler for JSX to JS
- JSX attributes become component props
- JSX attribute expression, literal string
- JSX attribute camel case
- props in JSX 
{{greeting: "Welcome"}}
JSX expression {}, object literal {}

- unescaping content 
    DangerouslySetInnerHtml={{__html:props.dangerous}}

<h1>
<Sum a = {3} a1 = {4} />
</h1>

JSX compiler
    JSX syntax to JS calls
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

