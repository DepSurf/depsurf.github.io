# Function: <code>radix_tree_node_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct radix_tree_node * radix_tree_node_alloc(struct radix_tree_root * root)
```

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582968608,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:181",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968608,
      "name": "radix_tree_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node * radix_tree_node_alloc(struct radix_tree_root * root)
```

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253248,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:265",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253248,
      "name": "radix_tree_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583373168,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:290",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:__radix_tree_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373168,
      "name": "radix_tree_node_alloc.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588222416,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:377",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222416,
      "name": "radix_tree_node_alloc.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772480,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:377",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free_cmn",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772480,
      "name": "radix_tree_node_alloc.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589151040,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:378",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151040,
      "name": "radix_tree_node_alloc.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589384576,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:255",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384576,
      "name": "radix_tree_node_alloc.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589841632,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841632,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590067728,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590067728,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585061920,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061920,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211216,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:__radix_tree_create",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211216,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585094192,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094192,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585541792,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541792,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586697408,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697408,
      "name": "radix_tree_node_alloc.constprop.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595858256,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:234",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595858256,
      "name": "radix_tree_node_alloc.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596375152,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:233",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375152,
      "name": "radix_tree_node_alloc.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597270400,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:233",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597270400,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503845200,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503845200,
      "name": "radix_tree_node_alloc.constprop.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236465044,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236465044,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297698944,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297698944,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279735724,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279735724,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589669984,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669984,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589395808,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395808,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590113360,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590113360,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590163744,
      "name": "radix_tree_node_alloc",
      "external": false,
      "loc": "lib/radix-tree.c:242",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_insert",
        "lib/radix-tree.c:radix_tree_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163744,
      "name": "radix_tree_node_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct radix_tree_node * radix_tree_node_alloc(struct radix_tree_root * root)
```
</details>
</li>
</ul>
