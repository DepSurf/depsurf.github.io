# Function: <code>perf_callchain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580443184,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:160",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443184,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518240,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518240,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580582208,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582208,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612864,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:182",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612864,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693664,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:182",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693664,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811904,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6356",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811904,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878544,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6365",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878544,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974720,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6443",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974720,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028848,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028848,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210400,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6962",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210400,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253120,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7133",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253120,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269792,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7244",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269792,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510784,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7368",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510784,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857440,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7273",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857440,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283872,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7540",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283872,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484832,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7553",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484832,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653536,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:7634",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653536,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492380744,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492380744,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226267704,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226267704,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285638352,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285638352,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272493432,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272493432,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997696,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997696,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943888,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943888,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988896,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988896,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct perf_callchain_entry * perf_callchain(struct perf_event * event, struct pt_regs * regs)
```

```json
{
  "name": "perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049840,
      "name": "perf_callchain",
      "external": true,
      "loc": "kernel/events/core.c:6559",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data",
        "arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049840,
      "name": "perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
