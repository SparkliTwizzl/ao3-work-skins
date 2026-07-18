Canonical styling rule ordering is as follows:
- Section
- Alphabetical by selector
  - Blanket rules take priority over individual rules

Additionally, properties should be organized alphabetically unless styling priority necessitates superceding this convention.

EXAMPLE
1 - Section A
.class-A .subclass-A element-A,
.class-A .subclass-B element-A {...}

.class-A .subclass-A element-A {...}

.class-A .subclass-A element-B {...}

.class-A .subclass-A.subclass-C element-A,
.class-A .subclass-B.subclass-C element-A {...}

.class-A .subclass-B element-A {...}

.class-B {...}

2 - Section B
.class-A .subclass-A element-A {...}
