# Installation
> `npm install --save @types/fs-readdir-recursive`

# Summary
This package contains type definitions for fs-readdir-recursive (https://github.com/fs-utils/fs-readdir-recursive).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/fs-readdir-recursive.
## [index.d.ts](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/fs-readdir-recursive/index.d.ts)
````ts
// Type definitions for fs-readdir-recursive 1.1
// Project: https://github.com/fs-utils/fs-readdir-recursive
// Definitions by: Paolo Scanferla <https://github.com/pscanf>
// Definitions: https://github.com/DefinitelyTyped/DefinitelyTyped

declare function readdirRecursive(
    path: string,
    filter?: (name: string, index: number, dir: string) => boolean,
): string[];

export = readdirRecursive;

````

### Additional Details
 * Last updated: Wed, 20 Jul 2022 07:32:21 GMT
 * Dependencies: none
 * Global values: none

# Credits
These definitions were written by [Paolo Scanferla](https://github.com/pscanf).
