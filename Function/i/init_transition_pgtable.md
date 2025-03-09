# Function: <code>init_transition_pgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220352,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:44",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220590,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:44",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579232747,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:44",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230352,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:46",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579245912,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:46",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258373,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:51",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579282037,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:51",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296272,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296272,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301824,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301824,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331600,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:123",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331600,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579333184,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:123",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333184,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579335920,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:123",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335920,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:123",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391216,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
    },
    {
      "addr": 18446744071592077371,
      "name": "init_transition_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:125",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457744,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1129
    },
    {
      "addr": 18446744071593843881,
      "name": "init_transition_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:125",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546896,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
    },
    {
      "addr": 18446744071595966628,
      "name": "init_transition_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:125",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562192,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
    },
    {
      "addr": 18446744071596484177,
      "name": "init_transition_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:122",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589728,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
    },
    {
      "addr": 18446744071597380455,
      "name": "init_transition_pgtable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297632,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297632,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579233824,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298832,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298832,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```

```json
{
  "name": "init_transition_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307664,
      "name": "init_transition_pgtable",
      "external": false,
      "loc": "arch/x86/kernel/machine_kexec_64.c:124",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307664,
      "name": "init_transition_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
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
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int init_transition_pgtable(struct kimage * image, pgd_t * pgd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
