# challenge 1h

## JS
### What will be the output ? and why
```
for (var i=0; i<10; i++) {
  setTimeout(() => {
    console.log(i)
  }, i*500)
}
```


### Object Destructuring
#### Please Console.log "Goodwin James lives at 45 Hollywood boulevard Los Angeles"

```
const myNestedObject = {
  lastNameB : "Goodwin",
  firstnameB : "James",
  address : {
    number : 45,
    street : "Hollywood boulevard",
    city : "Los Angeles"
  }

};

```

## Angular
## Setup

```sh
yarn
```

or

```sh
npm install
```

## Running the app

```sh
yarn start
```

or

```sh
npm start
```

## Entities Challenge
1. Update books.reducers to use EntityState to define State
2. Create an unsorted entity adapter for State and use it to initialize initialState
3. Update the reducer to use adapter methods
4. Use the adapter to replace the selectAll selector and to create a selectEntities selector
5. Update the selectActiveBool selector to use the selectEntities selector instead of the selectAll selector

## Form Challenge
1. Update The Book Model and create a property called "ref"
2. Add a field named "ref" to the form (html/ts)
3. Create a async validator called referenceValidator to check if reference already exist
(use bookService checkReference method)
4. Add the Async validator to the "ref" field

