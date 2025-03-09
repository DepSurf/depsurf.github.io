# Function: <code>__klp_free_objects</code>

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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020816,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020816,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071824,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071824,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131008,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:625",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131008,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109232,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:625",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109232,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113024,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:624",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113024,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:624",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255360,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071592147230,
      "name": "__klp_free_objects.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:624",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424560,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071593919937,
      "name": "__klp_free_objects.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:649",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664400,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071595991960,
      "name": "__klp_free_objects.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:664",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740592,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071596510150,
      "name": "__klp_free_objects.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:664",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825552,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071597409023,
      "name": "__klp_free_objects.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284189840,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284189840,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040560,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040560,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985872,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985872,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032096,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032096,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```

```json
{
  "name": "__klp_free_objects",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082800,
      "name": "__klp_free_objects",
      "external": false,
      "loc": "kernel/livepatch/core.c:603",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_nops",
        "kernel/livepatch/core.c:klp_free_patch_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082800,
      "name": "__klp_free_objects",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
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
void __klp_free_objects(struct klp_patch * patch, bool nops_only)
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
