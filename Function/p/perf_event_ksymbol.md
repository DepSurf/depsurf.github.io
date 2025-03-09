# Function: <code>perf_event_ksymbol</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7814",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983645,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580979152,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037655,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581033280,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:8481",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/bpf/trampoline.c:bpf_trampoline_lookup",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216295,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581213168,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:8663",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323531,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581256000,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:8792",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265420,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581274000,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:8911",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188278,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581515088,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:8816",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963342,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581861504,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:9093",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023352,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582288592,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:9121",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545490,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582489600,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:9191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__get_insn_slot",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/events/core.c:perf_event_bpf_event",
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449269,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582658320,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492385248,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492385248,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226272504,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226272504,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285644272,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285644272,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272458222,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272458222,
      "name": "perf_event_ksymbol.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936272497114,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006503,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581002128,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952631,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580948288,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997703,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580993328,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```

```json
{
  "name": "perf_event_ksymbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_ksymbol",
      "external": true,
      "loc": "kernel/events/core.c:7930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058791,
      "name": "perf_event_ksymbol.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581054384,
      "name": "perf_event_ksymbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char * sym)
```
</details>
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
