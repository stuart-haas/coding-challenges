# Week 2

> August 27, 2021

## The Challenge

Build a dynamic and reusable form with React or Vue that makes a post request to a mock api.

## Getting Started

Each template has boiler plate code already with a mock server that's running with [MirageJS](https://miragejs.com/docs/getting-started/introduction/). 

[Axios](https://github.com/axios/axios) is include in each template. Use it to interact with the server by making a request to `/api/users` or whatever resource you'd like to define.

[Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) is included in each template for styling.

The form data provided can be whatever you want but feel free to use what's been put in the template.

For **React**, fork this template on [CodeSandbox](https://codesandbox.io/s/react-form-178op).

For **Vue**, fork this template on [CodeSanbox](https://codesandbox.io/s/vue-form-brd07).

## Requirements

1. Form fields must be provided dynamically and at least two of them should be required.

2. Form fields can include default attributes but can also be provided with dynamic ones i.e. class, style, required, event handlers, etc.

3. The form must display a validation message if not all required fields are filled out.

4. The form can be reused and provided with different fields and any action or method and be able to process the request dynamically. Upon submit a success or failure message must be displayed depending on the response.
