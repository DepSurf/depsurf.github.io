# Function: <code>__mon_event_count</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123968,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:228",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123968,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138256,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:228",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138256,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148016,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:236",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148016,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214448,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:233",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214448,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227456,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227456,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229680,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229680,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253232,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253232,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246096,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:288",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246096,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
u64 __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248080,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:288",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248080,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
u64 __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:288",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288640,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071592070284,
      "name": "__mon_event_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
u64 __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:288",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342896,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071593836517,
      "name": "__mon_event_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:369",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412496,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071595963956,
      "name": "__mon_event_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:399",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424992,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071596481602,
      "name": "__mon_event_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:399",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454576,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071597377702,
      "name": "__mon_event_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228528,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228528,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163408,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163408,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229600,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229600,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "__mon_event_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235008,
      "name": "__mon_event_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235008,
      "name": "__mon_event_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read * rr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read * rr)
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
