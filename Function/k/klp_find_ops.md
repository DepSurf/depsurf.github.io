# Function: <code>klp_find_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579797496,
      "name": "klp_find_ops",
      "external": false,
      "loc": "kernel/livepatch/core.c:65",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_disable_func",
        "kernel/livepatch/core.c:klp_enable_object"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827218,
      "name": "klp_find_ops",
      "external": false,
      "loc": "kernel/livepatch/core.c:67",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_object"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579854834,
      "name": "klp_find_ops",
      "external": false,
      "loc": "kernel/livepatch/core.c:67",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_enable_object"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct klp_ops * klp_find_ops(long unsigned int old_addr)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863403,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:36",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862928,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct klp_ops * klp_find_ops(long unsigned int old_addr)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579904939,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:37",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:klp_unpatch_object"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904448,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct klp_ops * klp_find_ops(long unsigned int old_addr)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939254,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:37",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:klp_unpatch_object"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938720,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct klp_ops * klp_find_ops(long unsigned int old_addr)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986342,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:37",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:klp_unpatch_object"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985808,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580027910,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027728,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580078806,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078624,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580137631,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_func",
        "kernel/livepatch/patch.c:klp_unpatch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137936,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580115007,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_func",
        "kernel/livepatch/patch.c:klp_unpatch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115312,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580118591,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_func",
        "kernel/livepatch/patch.c:klp_unpatch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118896,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260709,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/livepatch/patch.c:klp_patch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261472,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430647,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_func",
        "kernel/livepatch/patch.c:klp_unpatch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430960,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672439,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_func",
        "kernel/livepatch/patch.c:klp_unpatch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672912,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580748341,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/livepatch/patch.c:klp_patch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749248,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580833413,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object",
        "kernel/livepatch/patch.c:klp_patch_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834368,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284202744,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284202416,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047542,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047360,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579992854,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992672,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039078,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038896,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(void * old_func)
```

```json
{
  "name": "klp_find_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580089798,
      "name": "klp_find_ops",
      "external": true,
      "loc": "kernel/livepatch/patch.c:25",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object",
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089616,
      "name": "klp_find_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct klp_ops * klp_find_ops(long unsigned int old_addr)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * old_func</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int old_addr</code>
</li>
</ul>
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
struct klp_ops * klp_find_ops(void * old_func)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct klp_ops * klp_find_ops(void * old_func)
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
struct klp_ops * klp_find_ops(void * old_func)
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
