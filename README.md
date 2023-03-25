# Getting Started with Create React App

## Five significant features of React
- Javascript Syntax Extension(JSX).
- Virtual DOM
- Debugging
- One-way data binding
- Additional extensions

## Five major advantages of React.
- It can be used for the development of web and mobile apps.
- It allows for the easy creation of dynamic applications.
- It is made up of reusable components.
- It has dedicated tools for easy debugging.
- It is fairly easy to learn.

## Who created React?
- It was created by Jordan Walker, a software engineer at Meta, formerly Facebook. It is still being maintained by the company.

## Notable differences between HTML and JSX.
- In HTML. multiple elements can be returned, while JSX only returns a single root element, hence the need to wrap multiple elemnts in a single parent tag.
- HTML elements have attributes; JSX elements have props.
- HTML allows the use of self-closing tags like <img>, while JSX requires tags to be explictly closed; <img> becomes <img /> in JSX.
- It is not necessary to use camelCasing for attributes and ids in HTML, while all HTML attributes and event references in JSX become camelCase.

## Browsers cannot read JSX because...
- JSX is not valid Javascript, so there is no built-in implementation for browsers to read and understand it. A transpiler is generally needed to translate it to React.