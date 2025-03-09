# Function: <code>__wait_for_cpus</code>

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
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183584,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:523",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183584,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:531",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195440,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071579196583,
      "name": "__wait_for_cpus.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:532",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184848,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071579185991,
      "name": "__wait_for_cpus.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197584,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579198786,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198672,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071579200897,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:524",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219632,
      "name": "__wait_for_cpus.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579221809,
      "name": "__wait_for_cpus.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:522",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214080,
      "name": "__wait_for_cpus.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071591255716,
      "name": "__wait_for_cpus.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:522",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216544,
      "name": "__wait_for_cpus.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071591199312,
      "name": "__wait_for_cpus.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:522",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254752,
      "name": "__wait_for_cpus.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071592067275,
      "name": "__wait_for_cpus.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197520,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071579199745,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132512,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071579134737,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198592,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071579200817,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```

```json
{
  "name": "__wait_for_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__wait_for_cpus",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203872,
      "name": "__wait_for_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071579206097,
      "name": "__wait_for_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int __wait_for_cpus(atomic_t * t, long long int timeout)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
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
int __wait_for_cpus(atomic_t * t, long long int timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __wait_for_cpus(atomic_t * t, long long int timeout)
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
