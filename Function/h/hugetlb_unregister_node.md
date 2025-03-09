# Function: <code>hugetlb_unregister_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580787472,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2532",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_exit",
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071584483441,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:237",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_one_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787472,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580911488,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2583",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071584830796,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:248",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911488,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580979504,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2689",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585024044,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:248",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979504,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026640,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2667",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585109004,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:248",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026640,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581136096,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2675",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585535228,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:265",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136096,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581276704,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2677",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585778876,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:265",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276704,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359648,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585911916,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:270",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359648,
      "name": "hugetlb_unregister_node",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581470384,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2739",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071586150856,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:568",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470384,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581534400,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071586299432,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534400,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742064,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:3139",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071587069896,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:577",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742064,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790656,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:3095",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071587154248,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:588",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790656,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581818448,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:3260",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071587041640,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:591",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818448,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105056,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:3545",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071587609592,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:610",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105056,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582547520,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:3930",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071588949128,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:613",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547520,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583087520,
      "name": "hugetlb_unregister_node",
      "external": true,
      "loc": "mm/hugetlb.c:4087",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node",
        "drivers/base/node.c:unregister_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583087520,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298112,
      "name": "hugetlb_unregister_node",
      "external": true,
      "loc": "mm/hugetlb.c:4117",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node",
        "drivers/base/node.c:unregister_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298112,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534688,
      "name": "hugetlb_unregister_node",
      "external": true,
      "loc": "mm/hugetlb.c:4375",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node",
        "drivers/base/node.c:unregister_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534688,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492965304,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446603336499128884,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492965304,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286384320,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 13835058055292319468,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286384320,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581503136,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071586062680,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503136,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581445440,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071585908632,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445440,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581494448,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071586248328,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494448,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void hugetlb_unregister_node(struct node * node)
```

```json
{
  "name": "hugetlb_unregister_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581561216,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "mm/hugetlb.c:2856",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_register_node"
      ]
    },
    {
      "addr": 18446744071586358344,
      "name": "hugetlb_unregister_node",
      "external": false,
      "loc": "drivers/base/node.c:574",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561216,
      "name": "hugetlb_unregister_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hugetlb_unregister_node(struct node * node)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hugetlb_unregister_node(struct node * node)
```
</details>
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
