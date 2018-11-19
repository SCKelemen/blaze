# blaze 🔥
A blazing fast, actor-based, modern programming language

## abstract

Blaze is a high-level programming language similar to C# and Go#. Blaze offers Actor-style concurrency, and is designed with cloud scale data analytics in mind. 

## motivation

Developers should feel familiar with the language and code from baremetal to cloud.

## Syntax

Blaze is part of a complete language systems that also include [Ember](https://github.com/sckelemen/ember) and [Ash](https://github.com/sckelemen/ash). These three language share the same core syntax, but each are extended to support their target niche.

### Comments
```Go
// line comment

/* 
   block / multiline comment 
*/

/* inline comment */
```

### Packages
```Go
package SomePackage        // the name of the package

import "AnotherPackage"    // a single-package import 

import (                   // a multipackage import
   "ThirdPackage",
   "FourthPackage",
   "FifthPackage" 
)
```

### Varaible Declarations
```coffee
let name = expression
let count = 5

const identifier = expression
const five = 5 // immutable

const five = 6 // five == 5

int five = 5 // explicitly typed
```



```pony 
actor Main {
  
}

```



## Actors

### Lifecycle
- PreStart()
- PreRestart()
- PostRestart()
- PostStop()

### Syntax 
```Go
// line comment

/* 
   block / multiline comment 
*/

/* inline comment */
```

```pony 
actor Main {
  
}

```


## CRDT


## P2P

## QUIC
