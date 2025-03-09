# Function: <code>pti_user_pagetable_walk_pmd</code>

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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602721876,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:180",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602721876,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 299
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382560,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:196",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382560,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410128,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:206",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410128,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425920,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071579426881,
      "name": "pti_user_pagetable_walk_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429088,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429088,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454512,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454512,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451376,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451376,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453840,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453840,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519232,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519232,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579603360,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603360,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716368,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716368,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729952,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729952,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764896,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:199",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764896,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424928,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424928,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354064,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354064,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424848,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424848,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434032,
      "name": "pti_user_pagetable_walk_pmd",
      "external": false,
      "loc": "arch/x86/mm/pti.c:200",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434032,
      "name": "pti_user_pagetable_walk_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
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
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pmd_t * pti_user_pagetable_walk_pmd(long unsigned int address)
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
