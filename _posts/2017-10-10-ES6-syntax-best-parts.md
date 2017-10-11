---
layout: post
title: ES6 syntax best parts
published: true
---

### Where to find info about ES6 new syntax and features

* [Exploring ES6 online book](http://exploringjs.com/es6)


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


#### Concatenating àrrays

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
```

