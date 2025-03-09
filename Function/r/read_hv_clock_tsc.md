# Function: <code>read_hv_clock_tsc</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024080,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:41",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024080,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579016848,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:47",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016848,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579017248,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:49",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017248,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579019984,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:52",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019984,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021664,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:53",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021664,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588006240,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:235",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006240,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588214016,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:224",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588214016,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589081952,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:329",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081952,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589082960,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:329",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082960,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969056,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:378",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969056,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589679120,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:375",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679120,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591183152,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:375",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183152,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592909504,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:385",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592909504,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596943872,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:410",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593348640,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
u64 read_hv_clock_tsc()
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597871344,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:410",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594102640,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587825872,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:224",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825872,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536032,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:224",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536032,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588168496,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:224",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168496,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```

```json
{
  "name": "read_hv_clock_tsc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588286352,
      "name": "read_hv_clock_tsc",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:224",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286352,
      "name": "read_hv_clock_tsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u64 read_hv_clock_tsc(struct clocksource * arg)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct clocksource * arg</code>
</li>
</ul>
</details>
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
u64 read_hv_clock_tsc(struct clocksource * arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 read_hv_clock_tsc(struct clocksource * arg)
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
