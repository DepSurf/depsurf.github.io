# Function: <code>radix_tree_free_nodes</code>

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
void radix_tree_free_nodes(struct radix_tree_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369040,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:754",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_join",
        "lib/radix-tree.c:__radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369040,
      "name": "radix_tree_free_nodes",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220624,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:871",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_destroy",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_join",
        "lib/radix-tree.c:__radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220624,
      "name": "radix_tree_free_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void radix_tree_free_nodes(struct radix_tree_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770592,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:870",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_destroy",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_join",
        "lib/radix-tree.c:__radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770592,
      "name": "radix_tree_free_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void radix_tree_free_nodes(struct radix_tree_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589149360,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:871",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_destroy",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_join",
        "lib/radix-tree.c:__radix_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149360,
      "name": "radix_tree_free_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589383717,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:678",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589840781,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590066877,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct xa_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585061680,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061680,
      "name": "radix_tree_free_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void radix_tree_free_nodes(struct xa_node * node)
```

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210976,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:idr_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210976,
      "name": "radix_tree_free_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585094027,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585541611,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586697063,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595857943,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:657",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596374839,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:656",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597270087,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:656",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503842676,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236461908,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297695136,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279734766,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589669133,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589394957,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590112509,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_free_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590162877,
      "name": "radix_tree_free_nodes",
      "external": false,
      "loc": "lib/radix-tree.c:665",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void radix_tree_free_nodes(struct radix_tree_node * node)
```
</details>
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
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void radix_tree_free_nodes(struct xa_node * node)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void radix_tree_free_nodes(struct xa_node * node)
```
</details>
</li>
</ul>
