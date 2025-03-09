# Function: <code>uncore_freerunning_hw_config</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951504,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951504,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953936,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953936,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958352,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:438",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578961024,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:438",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958352,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578961024,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959632,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:475",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578962416,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:475",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959632,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578962416,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964672,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578967712,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964672,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578967712,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977216,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:489",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578980256,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:489",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977216,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578980256,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989376,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:489",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578994000,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:489",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989376,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071578994000,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009152,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:505",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014912,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:505",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009152,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579014912,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009200,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:508",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014960,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:508",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009200,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579014960,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034128,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:508",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579039888,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:508",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034128,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579039888,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953936,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953936,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951728,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951728,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953872,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953872,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_freerunning_hw_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954448,
      "name": "uncore_freerunning_hw_config",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:435",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954448,
      "name": "uncore_freerunning_hw_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box * box, struct perf_event * event)
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
