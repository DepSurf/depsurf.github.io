# Function: <code>pti_user_pagetable_walk_pte</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602722818,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:222",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602895093,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:242",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411214,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:251",
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
      "addr": 18446744071579411214,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426903,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579426903,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430144,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579430144,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455687,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_clone_user_shared",
        "arch/x86/mm/pti.c:pti_setup_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455687,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591272939,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_clone_user_shared",
        "arch/x86/mm/pti.c:pti_setup_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591272939,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591215890,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
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
      "addr": 18446744071591215890,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592092580,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
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
      "addr": 18446744071592092580,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593859725,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
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
      "addr": 18446744071593859725,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716832,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071595971514,
      "name": "pti_user_pagetable_walk_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730400,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596489093,
      "name": "pti_user_pagetable_walk_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:244",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765344,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071597385715,
      "name": "pti_user_pagetable_walk_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425984,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579425984,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355104,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579355104,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425904,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579425904,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```

```json
{
  "name": "pti_user_pagetable_walk_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435088,
      "name": "pti_user_pagetable_walk_pte",
      "external": false,
      "loc": "arch/x86/mm/pti.c:245",
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
      "addr": 18446744071579435088,
      "name": "pti_user_pagetable_walk_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t * pti_user_pagetable_walk_pte(long unsigned int address)
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
