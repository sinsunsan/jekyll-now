---
layout: post
title: ES6 syntax best parts
published: true
---

### Where to find info about ES6 new syntax and features

* [Exploring ES6 online book](http://exploringjs.com/es6)


### Classes

Class are used everywhere in Angular, so worth double reading the manual of javascript [class in ES6](http://exploringjs.com/es6/ch_classes.html). 

* `;`` in class are allowed but ignored
* we can use getter of setter (that is not an angular syntax but an ES6 one )
````
get errorMessage() {
 // put a logic  to get error messasage
 Return erroMessage;
} 
````

 
### Destructuration 

````
private getDataUrl({org, project}) {
  console.log(org); 
  console.log(project); 
}
````

instead of 

````
private getDataUrl(data) {
  console.log(data.org); 
  console.log(data.project); 
}
````


### Fat arrow syntax




### 2 use cases of spread operator


#### Defaulting an object

````js
{
  ...state,
  error: null,
  pending: true,
}
````


with [lodash](https://lodash.com) the equivalent would be

````js
_.default(state, { error: null, pending: true });
````


#### Concatenating arrays

````js
import { OrganizationComponent,
         OrganizationCreateComponent,
         OrganizationProfileComponent } from 'organizations';

import { OtherComponent1, OtherComponent2 } from 'others';

const organizationModules = [
  OrganizationComponent, 
  OrganizationCreateComponent,
];

const otherComponents = [
  OtherComponent1,
  OtherComponent2
]; 

const commonModules = [
  ...organizationModules, 
  ...otherComponents,
  { customObject: test },
]
````

### Modules and imports 

* [ES6 modules import syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)


### Async / Await 

* https://javascript.info/async