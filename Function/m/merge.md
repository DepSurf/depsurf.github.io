# Function: <code>merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017312,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071583056704,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017312,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583056704,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308320,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071583350480,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308320,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583350480,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427632,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071583475856,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427632,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583475856,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448960,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583498064,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448960,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583498064,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629056,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:17",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583680096,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629056,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071583680096,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845616,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:17",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583897984,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:522",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845616,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071583897984,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, int (*)(void *, struct list_head *, struct list_head *) cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929312,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:17",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583982256,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:522",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929312,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071583982256,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109189,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164752,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164752,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584232037,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584298448,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298448,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638901,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584708656,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708656,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584758437,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821840,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821840,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786885,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866512,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866512,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585217653,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585289280,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289280,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055264,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071586143040,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055264,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071586143040,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039104,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071587135952,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:516",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039104,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071587135952,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587296208,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071587398096,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:516",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296208,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071587398096,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
struct list_head * merge(void * priv, list_cmp_func_t cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587582032,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:16",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ]
    },
    {
      "addr": 18446744071587732448,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:516",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587582032,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071587732448,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496107420,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496184888,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496184888,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229432688,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 3229505436,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229505436,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290355288,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290461840,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290461840,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275173156,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275237316,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275237316,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584200773,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584267184,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267184,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584135989,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202384,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202384,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584184533,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584250944,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250944,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct list_head * merge(void * priv, cmp_func cmp, struct list_head * a, struct list_head * b)
```

```json
{
  "name": "merge",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288885,
      "name": "merge",
      "external": false,
      "loc": "lib/list_sort.c:19",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/list_sort.c:list_sort",
        "lib/list_sort.c:list_sort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584355872,
      "name": "merge",
      "external": false,
      "loc": "lib/btree.c:520",
      "file": "lib/btree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/btree.c:btree_remove_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355872,
      "name": "merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(void *, struct list_head *, struct list_head *) cmp</code> ➡️ <code>cmp_func cmp</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cmp_func cmp</code> ➡️ <code>list_cmp_func_t cmp</code>
</li>
</ul>
</details>
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
