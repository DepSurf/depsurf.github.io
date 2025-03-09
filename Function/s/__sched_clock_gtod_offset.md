# Function: <code>__sched_clock_gtod_offset</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682944,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:198",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682944,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716752,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716752,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759184,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759184,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579793249,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792688,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784097,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783536,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792209,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791648,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887982,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_tick_stable"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887392,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177421,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:197",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_clock_tick_stable"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593882432,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580362029,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:197",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580431757,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:197",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_init"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580490957,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:197",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735104,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735104,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663904,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663904,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719552,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719552,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
```

```json
{
  "name": "__sched_clock_gtod_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766864,
      "name": "__sched_clock_gtod_offset",
      "external": false,
      "loc": "kernel/sched/clock.c:199",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766864,
      "name": "__sched_clock_gtod_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void __sched_clock_gtod_offset()
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __sched_clock_gtod_offset()
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
void __sched_clock_gtod_offset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __sched_clock_gtod_offset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __sched_clock_gtod_offset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __sched_clock_gtod_offset()
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
