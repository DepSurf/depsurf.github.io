# Function: <code>genradix_free_recurse</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147008,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:184",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147008,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584270208,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584270208,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584678128,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678128,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584795744,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795744,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584840696,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839888,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585260296,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259488,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586103160,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102272,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587088152,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087248,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587348010,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346560,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587632042,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:274",
      "file": "lib/generic-radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587630592,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496153800,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496153800,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229474308,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229474308,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290416160,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290416160,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275206670,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275206670,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584238944,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584238944,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174144,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174144,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584222704,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222704,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```

```json
{
  "name": "genradix_free_recurse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584327536,
      "name": "genradix_free_recurse",
      "external": false,
      "loc": "lib/generic-radix-tree.c:204",
      "file": "lib/generic-radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:genradix_free_recurse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327536,
      "name": "genradix_free_recurse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void genradix_free_recurse(struct genradix_node * n, unsigned int level)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
