# Function: <code>nmi_uaccess_okay</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878151,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:264",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589205097,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:264",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877863,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589446681,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878618,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689321,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589904585,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879162,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580736281,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590130569,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417312,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1224",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417312,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417392,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1160",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417392,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420480,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1200",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420480,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484032,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1259",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484032,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563344,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1229",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563344,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670976,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1254",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670976,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684928,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "mm/maccess.c:copy_from_user_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684928,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool nmi_uaccess_okay()
```

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719440,
      "name": "nmi_uaccess_okay",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1284",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user",
        "mm/maccess.c:copy_from_user_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719440,
      "name": "nmi_uaccess_okay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879162,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580705081,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589732825,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873002,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651289,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589458505,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879098,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696329,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590176201,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nmi_uaccess_okay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879450,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751849,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_probe_write_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226649,
      "name": "nmi_uaccess_okay",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool nmi_uaccess_okay()
```
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
