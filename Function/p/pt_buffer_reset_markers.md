# Function: <code>pt_buffer_reset_markers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578926848,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:678",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_add",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578926848,
      "name": "pt_buffer_reset_markers.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578925600,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:819",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578925600,
      "name": "pt_buffer_reset_markers.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578925984,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:840",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578925984,
      "name": "pt_buffer_reset_markers.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578916880,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:917",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916880,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578918736,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:918",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918736,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578920672,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:918",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578920672,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578922464,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:928",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578922464,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578927472,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:920",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927472,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578929872,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1026",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929872,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938992,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1061",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938992,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578940176,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1061",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940176,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578944240,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1061",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578944240,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1062",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954768,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071592043846,
      "name": "pt_buffer_reset_markers.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1080",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963680,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071593810258,
      "name": "pt_buffer_reset_markers.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1080",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981056,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071595954599,
      "name": "pt_buffer_reset_markers.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1080",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980368,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071596471770,
      "name": "pt_buffer_reset_markers.cold",
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1081",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579005232,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071597367112,
      "name": "pt_buffer_reset_markers.cold",
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578929872,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1026",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929872,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578926496,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1026",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578926496,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578929808,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1026",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929808,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```

```json
{
  "name": "pt_buffer_reset_markers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578930384,
      "name": "pt_buffer_reset_markers",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:1026",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578930384,
      "name": "pt_buffer_reset_markers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
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
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer * buf, struct perf_output_handle * handle)
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
