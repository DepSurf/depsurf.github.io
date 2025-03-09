# Function: <code>watchdog_nmi_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580134276,
      "name": "watchdog_nmi_enable",
      "external": false,
      "loc": "kernel/watchdog.c:572",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_enable"
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
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168372,
      "name": "watchdog_nmi_enable",
      "external": false,
      "loc": "kernel/watchdog.c:588",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_enable"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209312,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:246",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210848,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216848,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:122",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219056,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267984,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:109",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267984,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328240,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:109",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328240,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381424,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381424,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434128,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434128,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482896,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482896,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567760,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:100",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567760,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580555632,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:98",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580555632,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558912,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:98",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558912,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728864,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:98",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728864,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941248,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:98",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941248,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 22
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234704,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:98",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234704,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 22
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491758936,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491758936,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225707276,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225707276,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284800544,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284800544,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272080148,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272080148,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451696,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451696,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580398768,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398768,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442944,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442944,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 18
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
int watchdog_nmi_enable(unsigned int cpu)
```

```json
{
  "name": "watchdog_nmi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498576,
      "name": "watchdog_nmi_enable",
      "external": true,
      "loc": "kernel/watchdog.c:105",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498576,
      "name": "watchdog_nmi_enable",
      "section": ".text",
      "bind": "STB_WEAK",
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int watchdog_nmi_enable(unsigned int cpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
