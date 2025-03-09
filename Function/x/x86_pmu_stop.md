# Function: <code>x86_pmu_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868224,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1289",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868224,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868896,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1316",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868896,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868704,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1336",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868704,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868080,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1337",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868080,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578868944,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1343",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868944,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870880,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1346",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870880,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870704,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1347",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870704,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871264,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1386",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871264,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871408,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1456",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871408,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875856,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1457",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875856,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871936,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1534",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871936,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872272,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1589",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872272,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578874064,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1587",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578874064,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871232,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1595",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871232,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870512,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1584",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870512,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578868368,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1584",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868368,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578890640,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1582",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890640,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871408,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1456",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871408,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865040,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1456",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865040,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871344,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1456",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871344,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```

```json
{
  "name": "x86_pmu_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578871696,
      "name": "x86_pmu_stop",
      "external": true,
      "loc": "arch/x86/events/core.c:1456",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_handle_irq",
        "arch/x86/events/core.c:x86_pmu_del",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871696,
      "name": "x86_pmu_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void x86_pmu_stop(struct perf_event * event, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void x86_pmu_stop(struct perf_event * event, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void x86_pmu_stop(struct perf_event * event, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void x86_pmu_stop(struct perf_event * event, int flags)
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
