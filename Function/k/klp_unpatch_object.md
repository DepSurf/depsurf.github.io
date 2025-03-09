# Function: <code>klp_unpatch_object</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579862992,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:238",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_going",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862992,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904512,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:239",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904512,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938784,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:239",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938784,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985872,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:239",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985872,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028216,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027792,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079114,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078688,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580138175,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:255",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138000,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580115551,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:262",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115376,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580119135,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:262",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118960,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261662,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:262",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261536,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580431166,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:247",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431040,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673150,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:247",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673008,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580749486,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:247",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749344,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580834606,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:247",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834464,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284203268,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284202528,
      "name": "klp_unpatch_object",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047850,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047424,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579993162,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992736,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039386,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038960,
      "name": "klp_unpatch_object",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```

```json
{
  "name": "klp_unpatch_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090106,
      "name": "klp_unpatch_object",
      "external": true,
      "loc": "kernel/livepatch/patch.c:254",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_cleanup_module_patches_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089680,
      "name": "klp_unpatch_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_unpatch_object(struct klp_object * obj)
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
void klp_unpatch_object(struct klp_object * obj)
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
