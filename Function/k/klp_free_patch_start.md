# Function: <code>klp_free_patch_start</code>

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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022848,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022848,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073872,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073872,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580134732,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:657",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580112956,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:657",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580116710,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:656",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580259076,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:656",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580428440,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:656",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580669337,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:681",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580745124,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:696",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
  "name": "klp_free_patch_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830196,
      "name": "klp_free_patch_start",
      "external": false,
      "loc": "kernel/livepatch/core.c:696",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_replaced_patches_async"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284194848,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284194848,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042608,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042608,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987920,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987920,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034144,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034144,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void klp_free_patch_start(struct klp_patch * patch)
```

```json
{
  "name": "klp_free_patch_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084848,
      "name": "klp_free_patch_start",
      "external": true,
      "loc": "kernel/livepatch/core.c:635",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_discard_replaced_patches",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084848,
      "name": "klp_free_patch_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void klp_free_patch_start(struct klp_patch * patch)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void klp_free_patch_start(struct klp_patch * patch)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void klp_free_patch_start(struct klp_patch * patch)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_free_patch_start(struct klp_patch * patch)
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
void klp_free_patch_start(struct klp_patch * patch)
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
