# Function: <code>intel_pmu_auto_reload_read</code>

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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910816,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1331",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910816,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578912320,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1342",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912320,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1610",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916965,
      "name": "intel_pmu_auto_reload_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578916816,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578918864,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1653",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918864,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578924096,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1654",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578924096,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578922992,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1659",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578922992,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578927616,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1779",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927616,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578932576,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1788",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932576,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578940768,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1846",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940768,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957632,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1905",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957632,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956816,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1959",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956816,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578980208,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1964",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980208,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578918864,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1653",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918864,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578914352,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1653",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914352,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578918800,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1653",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918800,
      "name": "intel_pmu_auto_reload_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```

```json
{
  "name": "intel_pmu_auto_reload_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578919344,
      "name": "intel_pmu_auto_reload_read",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:1653",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578919344,
      "name": "intel_pmu_auto_reload_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void intel_pmu_auto_reload_read(struct perf_event * event)
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
void intel_pmu_auto_reload_read(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event * event)
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
