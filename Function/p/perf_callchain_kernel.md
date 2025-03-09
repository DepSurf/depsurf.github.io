# Function: <code>perf_callchain_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875360,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2185",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875360,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875744,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2273",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875744,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875744,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2280",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875744,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875120,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2302",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875120,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578876192,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2337",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876192,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877776,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2343",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877776,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877488,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2359",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877488,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878192,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2321",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878192,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878736,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2410",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878736,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578882944,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2423",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578882944,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879024,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2534",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578879024,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881536,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2764",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881536,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2763",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592039324,
      "name": "perf_callchain_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071578885264,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2777",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805412,
      "name": "perf_callchain_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071578883024,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2761",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595950955,
      "name": "perf_callchain_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071578888288,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2759",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596468169,
      "name": "perf_callchain_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071578886320,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2756",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597363205,
      "name": "perf_callchain_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071578908624,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490301736,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/arm64/kernel/perf_callchain.c:147",
      "file": "arch/arm64/kernel/perf_callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490301736,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224468980,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/arm/kernel/perf_callchain.c:99",
      "file": "arch/arm/kernel/perf_callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224468980,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283365184,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/powerpc/perf/callchain.c:47",
      "file": "arch/powerpc/perf/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283365184,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271358428,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/riscv/kernel/perf_callchain.c:84",
      "file": "arch/riscv/kernel/perf_callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271358428,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878736,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2410",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878736,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872576,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2410",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872576,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878672,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2410",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878672,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void perf_callchain_kernel(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879024,
      "name": "perf_callchain_kernel",
      "external": true,
      "loc": "arch/x86/events/core.c:2410",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578879024,
      "name": "perf_callchain_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct perf_callchain_entry * entry</code> ➡️ <code>struct perf_callchain_entry_ctx * entry</code>
</li>
</ul>
</details>
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
