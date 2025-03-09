# Function: <code>radix_tree_iter_replace</code>

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
void radix_tree_iter_replace(struct radix_tree_root * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375776,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1115",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375776,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void radix_tree_iter_replace(struct radix_tree_root * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225104,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1241",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225104,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void radix_tree_iter_replace(struct radix_tree_root * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775152,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1239",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc_cmn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775152,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void radix_tree_iter_replace(struct radix_tree_root * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153808,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1240",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:ida_get_new_above",
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153808,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386368,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:952",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386368,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843440,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843440,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069536,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069536,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066592,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:931",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066592,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215920,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:931",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215920,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098752,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:932",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098752,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547008,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:932",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547008,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702864,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:932",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702864,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595864640,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:932",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595864640,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596381984,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:931",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596381984,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597277232,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:931",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597277232,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503847488,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503847488,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236467132,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236467132,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297701712,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297701712,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279737414,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279737414,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671792,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671792,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397616,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397616,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115168,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115168,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct xarray * root, const struct radix_tree_iter * iter, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_iter_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165552,
      "name": "radix_tree_iter_replace",
      "external": true,
      "loc": "lib/radix-tree.c:939",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165552,
      "name": "radix_tree_iter_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void radix_tree_iter_replace(struct radix_tree_root * root, const struct radix_tree_iter * iter, void * * slot, void * item)
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
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
