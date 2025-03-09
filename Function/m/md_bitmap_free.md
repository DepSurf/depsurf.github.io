# Function: <code>md_bitmap_free</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426112,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1734",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426112,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587698016,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587698016,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587902304,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902304,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588750640,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1730",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750640,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770880,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1731",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770880,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588658000,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1733",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658000,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589335872,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1733",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335872,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590809232,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1734",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590809232,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592495568,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1734",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592495568,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592925888,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1801",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592925888,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593676528,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1805",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593676528,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501128672,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501128672,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233649692,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233649692,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294636192,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294636192,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277847374,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277847374,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587533280,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533280,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587301440,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587301440,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587858448,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587858448,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void md_bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977328,
      "name": "md_bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1735",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977328,
      "name": "md_bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void md_bitmap_free(struct bitmap * bitmap)
```
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
