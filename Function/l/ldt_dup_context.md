# Function: <code>ldt_dup_context</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050752,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:252",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050752,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056112,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:256",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056112,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061072,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061072,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068944,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068944,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071040,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071040,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078896,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078896,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081248,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081248,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088112,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:449",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088112,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111248,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:449",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111248,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142768,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:449",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142768,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187152,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:449",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187152,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191216,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:451",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191216,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220464,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:451",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220464,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071392,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071392,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579004304,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579004304,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070976,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070976,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```

```json
{
  "name": "ldt_dup_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075072,
      "name": "ldt_dup_context",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:359",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075072,
      "name": "ldt_dup_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```
</details>
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
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ldt_dup_context(struct mm_struct * old_mm, struct mm_struct * mm)
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
