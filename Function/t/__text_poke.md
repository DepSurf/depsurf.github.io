# Function: <code>__text_poke</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080448,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
    },
    {
      "addr": 18446744071579084168,
      "name": "__text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082448,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082448,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093824,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:843",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093824,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095040,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:855",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095040,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101200,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:776",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101200,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125120,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:776",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125120,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
void * __text_poke(text_poke_f * func, void * addr, const void * src, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159488,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1082",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159488,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1121
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
void * __text_poke(text_poke_f * func, void * addr, const void * src, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209680,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1545",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209680,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1121
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
void * __text_poke(text_poke_f * func, void * addr, const void * src, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215232,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1770",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215232,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
void * __text_poke(text_poke_f * func, void * addr, const void * src, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244496,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1860",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244496,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082800,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082800,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579015440,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015440,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082384,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082384,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "__text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579086480,
      "name": "__text_poke",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:788",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_kgdb",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086480,
      "name": "__text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
void * __text_poke(void * addr, const void * opcode, size_t len)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>text_poke_f * func</code>
</li>
<li>
<b>Param added. </b>
<code>const void * src</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * opcode</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, opcode, len</code> ➡️ <code>func, addr, src, len</code>
</li>
</ul>
</details>
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
void * __text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * __text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * __text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * __text_poke(void * addr, const void * opcode, size_t len)
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
