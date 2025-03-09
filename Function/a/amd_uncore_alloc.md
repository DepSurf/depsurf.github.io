# Function: <code>amd_uncore_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578880718,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:287",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881055,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881119,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:291",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578880414,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:313",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578880958,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:313",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578882782,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:314",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881952,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:322",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881952,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578883120,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:323",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883120,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884144,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:320",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884144,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578889120,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:338",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889120,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884912,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:365",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884912,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578887440,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:365",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887440,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884144,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:320",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884144,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877904,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:320",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877904,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884080,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:320",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884080,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```

```json
{
  "name": "amd_uncore_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884432,
      "name": "amd_uncore_alloc",
      "external": false,
      "loc": "arch/x86/events/amd/uncore.c:320",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884432,
      "name": "amd_uncore_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
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
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct amd_uncore * amd_uncore_alloc(unsigned int cpu)
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
