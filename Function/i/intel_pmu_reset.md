# Function: <code>intel_pmu_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895780,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1788",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578896404,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2017",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578896604,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2020",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895904,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2155",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578897356,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2155",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578899197,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2163",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578891648,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2214",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578891648,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578893200,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2291",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578893200,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578894240,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2292",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894240,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578906464,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2299",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578906464,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578903248,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2559",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903248,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578907264,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2741",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578907264,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2743",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910800,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071592041441,
      "name": "intel_pmu_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2811",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916432,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071593807636,
      "name": "intel_pmu_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2844",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578931312,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    },
    {
      "addr": 18446744071595952015,
      "name": "intel_pmu_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2864",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929360,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071596469205,
      "name": "intel_pmu_reset.cold",
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2872",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949824,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071597364245,
      "name": "intel_pmu_reset.cold",
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578894240,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2292",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894240,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578897664,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2292",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897664,
      "name": "intel_pmu_reset",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578894176,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2292",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894176,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
```

```json
{
  "name": "intel_pmu_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578894736,
      "name": "intel_pmu_reset",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2292",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894736,
      "name": "intel_pmu_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void intel_pmu_reset()
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
void intel_pmu_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pmu_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pmu_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pmu_reset()
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
