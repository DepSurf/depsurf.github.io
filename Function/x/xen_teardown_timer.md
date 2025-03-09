# Function: <code>xen_teardown_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991008,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:396",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991008,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987584,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:305",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987584,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578989456,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:305",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_cpu_dead",
        "arch/x86/xen/time.c:xen_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989456,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578956200,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:309",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955856,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958504,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:310",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958160,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578960688,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:310",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960688,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959440,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959440,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966416,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966416,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968880,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968880,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978370,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:324",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978224,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980994,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:325",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980848,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990114,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:325",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989968,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007085,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:325",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579006896,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024397,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:325",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024208,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052675,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:325",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052240,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052579,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:333",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052144,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077907,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:333",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_setup_timer"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077472,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968896,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968896,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968816,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968816,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xen_teardown_timer(int cpu)
```

```json
{
  "name": "xen_teardown_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969440,
      "name": "xen_teardown_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969440,
      "name": "xen_teardown_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
void xen_teardown_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_teardown_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_teardown_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_teardown_timer(int cpu)
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
void xen_teardown_timer(int cpu)
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
