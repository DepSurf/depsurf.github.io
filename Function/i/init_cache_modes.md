# Function: <code>init_cache_modes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302646,
      "name": "init_cache_modes",
      "external": false,
      "loc": "arch/x86/mm/pat.c:244",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302016,
      "name": "init_cache_modes.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318054,
      "name": "init_cache_modes",
      "external": false,
      "loc": "arch/x86/mm/pat.c:244",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317424,
      "name": "init_cache_modes.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579315328,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:246",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315328,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338240,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:246",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338240,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579349616,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:246",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349616,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376560,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:246",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376560,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392080,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392080,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395392,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395392,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434176,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:275",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434176,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433408,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:275",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433408,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436224,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:275",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436224,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:275",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088819,
      "name": "init_cache_modes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579500240,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617071899,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:277",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617071899,
      "name": "init_cache_modes",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void init_cache_modes(u64 pat)
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627721776,
      "name": "init_cache_modes",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:217",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627721776,
      "name": "init_cache_modes",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 185
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
void init_cache_modes(u64 pat)
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619479376,
      "name": "init_cache_modes",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:217",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619479376,
      "name": "init_cache_modes",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 185
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
void init_cache_modes(u64 pat)
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621775984,
      "name": "init_cache_modes",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:217",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621775984,
      "name": "init_cache_modes",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 185
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391296,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391296,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320848,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320848,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391216,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391216,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
```

```json
{
  "name": "init_cache_modes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399744,
      "name": "init_cache_modes",
      "external": true,
      "loc": "arch/x86/mm/pat.c:247",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399744,
      "name": "init_cache_modes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_cache_modes()
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 pat</code>
</li>
</ul>
</details>
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
void init_cache_modes()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void init_cache_modes()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void init_cache_modes()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void init_cache_modes()
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
