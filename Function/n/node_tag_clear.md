# Function: <code>node_tag_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583256576,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:790",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_replace_clear_tags",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256576,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372288,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1305",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_clear_tags",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372288,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588221584,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1463",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_clear_tags",
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221584,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588771568,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1461",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_clear_tags",
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771568,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589150320,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1462",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_clear_tags",
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150320,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589383872,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1016",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383872,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589840912,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840912,
      "name": "node_tag_clear",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590067008,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590067008,
      "name": "node_tag_clear",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585063312,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:995",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063312,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585212608,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:995",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212608,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095248,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:996",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095248,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585543020,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:996",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542944,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071592342819,
      "name": "node_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:996",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698128,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071594204387,
      "name": "node_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595859101,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:996",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595859008,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071596373586,
      "name": "node_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596376047,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:995",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375904,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071596903251,
      "name": "node_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597271295,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:995",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597271152,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071597828344,
      "name": "node_tag_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503844344,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503844344,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236463796,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236463796,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297697568,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297697568,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279734878,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279734878,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589669264,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669264,
      "name": "node_tag_clear",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589395088,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395088,
      "name": "node_tag_clear",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112640,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112640,
      "name": "node_tag_clear",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void node_tag_clear(struct xarray * root, struct xa_node * node, unsigned int tag, unsigned int offset)
```

```json
{
  "name": "node_tag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590163008,
      "name": "node_tag_clear",
      "external": false,
      "loc": "lib/radix-tree.c:1003",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_iter_tag_clear",
        "lib/radix-tree.c:radix_tree_tag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163008,
      "name": "node_tag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void node_tag_clear(struct radix_tree_root * root, struct radix_tree_node * node, unsigned int tag, unsigned int offset)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node * node</code> ➡️ <code>struct xa_node * node</code>
</li>
</ul>
</details>
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
