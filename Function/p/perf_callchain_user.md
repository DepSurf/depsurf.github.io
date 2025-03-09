# Function: <code>perf_callchain_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_callchain_user(struct perf_callchain_entry * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875456,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2279",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875456,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875856,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2375",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875856,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876016,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2388",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876016,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875392,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2407",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875392,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876464,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2442",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876464,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878048,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2448",
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
      "addr": 18446744071578878048,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877760,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2464",
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
      "addr": 18446744071578877760,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878512,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2430",
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
      "addr": 18446744071578878512,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879056,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2519",
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
      "addr": 18446744071578879056,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578883264,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2526",
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
      "addr": 18446744071578883264,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879344,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2637",
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
      "addr": 18446744071578879344,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881856,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2867",
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
      "addr": 18446744071578881856,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527712,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2867",
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
      "addr": 18446744071592039380,
      "name": "perf_callchain_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071578885616,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875648,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2880",
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
      "addr": 18446744071593805468,
      "name": "perf_callchain_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071578883392,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303424,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2864",
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
      "addr": 18446744071595951011,
      "name": "perf_callchain_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071578888672,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504208,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2862",
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
      "addr": 18446744071596468225,
      "name": "perf_callchain_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071578886704,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672752,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2859",
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
      "addr": 18446744071597363261,
      "name": "perf_callchain_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071578909008,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490300560,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/arm64/kernel/perf_callchain.c:102",
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
      "addr": 18446603336490300560,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224468420,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/arm/kernel/perf_callchain.c:63",
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
      "addr": 3224468420,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283365856,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/powerpc/perf/callchain.c:487",
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
      "addr": 13835058055283365856,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1920
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271358274,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/riscv/kernel/perf_callchain.c:60",
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
      "addr": 18446743936271358274,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879056,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2519",
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
      "addr": 18446744071578879056,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872896,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2519",
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
      "addr": 18446744071578872896,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578878992,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2519",
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
      "addr": 18446744071578878992,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void perf_callchain_user(struct perf_callchain_entry_ctx * entry, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879344,
      "name": "perf_callchain_user",
      "external": true,
      "loc": "arch/x86/events/core.c:2519",
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
      "addr": 18446744071578879344,
      "name": "perf_callchain_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
