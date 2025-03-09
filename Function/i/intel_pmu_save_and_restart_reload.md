# Function: <code>intel_pmu_save_and_restart_reload</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904432,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1344",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904432,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578905664,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1355",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905664,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1623",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578907952,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071578916927,
      "name": "intel_pmu_save_and_restart_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909696,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1666",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909696,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915424,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1667",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915424,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578912912,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1672",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912912,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578916912,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1792",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916912,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1801",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578920688,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071592042070,
      "name": "intel_pmu_save_and_restart_reload.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1859",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927840,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071593808236,
      "name": "intel_pmu_save_and_restart_reload.isra.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1918",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578944672,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071595952607,
      "name": "intel_pmu_save_and_restart_reload.isra.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1972",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942848,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071596469788,
      "name": "intel_pmu_save_and_restart_reload.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1977",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966256,
      "name": "intel_pmu_save_and_restart_reload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071597364923,
      "name": "intel_pmu_save_and_restart_reload.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909696,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1666",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909696,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904928,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1666",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904928,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909632,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1666",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909632,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```

```json
{
  "name": "intel_pmu_save_and_restart_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910160,
      "name": "intel_pmu_save_and_restart_reload",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1666",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:__intel_pmu_pebs_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910160,
      "name": "intel_pmu_save_and_restart_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
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
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event * event, int count)
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
