# Function: <code>x86_setup_perfctr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870128,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:386",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870128,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870656,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:397",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870656,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870672,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:402",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870672,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870064,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:403",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870064,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870960,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:403",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870960,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872864,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:407",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872864,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872672,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:407",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872672,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873200,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:407",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873200,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873328,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:412",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873328,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877520,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:413",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877520,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873600,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:445",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873600,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875424,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:471",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875424,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877680,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:471",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877680,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578874992,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:473",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578874992,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881296,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:476",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881296,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578879296,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:476",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578879296,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578901600,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:474",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578901600,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873328,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:412",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873328,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866960,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:412",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866960,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873264,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:412",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873264,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```

```json
{
  "name": "x86_setup_perfctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873616,
      "name": "x86_setup_perfctr",
      "external": true,
      "loc": "arch/x86/events/core.c:412",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_hw_config",
        "arch/x86/events/intel/p4.c:p4_hw_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873616,
      "name": "x86_setup_perfctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int x86_setup_perfctr(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int x86_setup_perfctr(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int x86_setup_perfctr(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int x86_setup_perfctr(struct perf_event * event)
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
