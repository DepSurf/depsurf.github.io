# Function: <code>delete_node</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void delete_node(struct radix_tree_root * root, struct radix_tree_node * node, radix_tree_update_node_t update_node, void * private)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371776,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:648",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete_node",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371776,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root * root, struct radix_tree_node * node, radix_tree_update_node_t update_node, void * private)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220848,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:753",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_delete_node",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220848,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root * root, struct radix_tree_node * node, radix_tree_update_node_t update_node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770816,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:752",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_delete_node",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770816,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root * root, struct radix_tree_node * node, radix_tree_update_node_t update_node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589149600,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:753",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_delete_node",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149600,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383136,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:565",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383136,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589840224,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840224,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066320,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066320,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062112,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062112,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211408,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211408,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094384,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094384,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541984,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541984,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696416,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696416,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595861168,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:544",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595861168,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596378384,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:543",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596378384,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597273632,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:543",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597273632,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503842120,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503842120,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236461128,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236461128,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297694288,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297694288,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279734260,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279734260,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668576,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668576,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589394400,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589394400,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111952,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111952,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
bool delete_node(struct xarray * root, struct xa_node * node)
```

```json
{
  "name": "delete_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162320,
      "name": "delete_node",
      "external": false,
      "loc": "lib/radix-tree.c:552",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162320,
      "name": "delete_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void delete_node(struct radix_tree_root * root, struct radix_tree_node * node, radix_tree_update_node_t update_node, void * private)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * private</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>radix_tree_update_node_t update_node</code>
</li>
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
