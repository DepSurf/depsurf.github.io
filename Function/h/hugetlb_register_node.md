# Function: <code>hugetlb_register_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788544,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2576",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071584483397,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:227",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788544,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580911728,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2608",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584830696,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:238",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911728,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580979744,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2714",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585023956,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:238",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979744,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026864,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2692",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585108919,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:238",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026864,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581136320,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2700",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585535128,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:255",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136320,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2702",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071585778617,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:255",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276944,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581304976,
      "name": "hugetlb_register_node.cold.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2696",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071585911733,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:260",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359888,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581388644,
      "name": "hugetlb_register_node.cold.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2764",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071586152744,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:558",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470624,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581500279,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071586301224,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534640,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581564791,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:3164",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071587071650,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:567",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744496,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071581775567,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:3120",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071587156194,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:578",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790896,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071591332363,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:3285",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071587043506,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:581",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818688,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071591275047,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:3570",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071587611901,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:600",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105376,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071592210858,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:3955",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071588951670,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:603",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547856,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    },
    {
      "addr": 18446744071593989113,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": true,
      "loc": "mm/hugetlb.c:4117",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "drivers/base/node.c:__register_one_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596041813,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583087936,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": true,
      "loc": "mm/hugetlb.c:4147",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "drivers/base/node.c:__register_one_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596564078,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583298592,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": true,
      "loc": "mm/hugetlb.c:4405",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "drivers/base/node.c:__register_one_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597469492,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583535168,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492965528,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446603336499134892,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492965528,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286384656,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 13835058055292325372,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286384656,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071586064472,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503376,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581533527,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071585910424,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445680,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581475303,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071586249304,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494688,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581524839,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void hugetlb_register_node(struct node * node)
```

```json
{
  "name": "hugetlb_register_node",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "mm/hugetlb.c:2881",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071586360136,
      "name": "hugetlb_register_node",
      "external": false,
      "loc": "drivers/base/node.c:564",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:node_hugetlb_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561456,
      "name": "hugetlb_register_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581589752,
      "name": "hugetlb_register_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void hugetlb_register_node(struct node * node)
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
void hugetlb_register_node(struct node * node)
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
