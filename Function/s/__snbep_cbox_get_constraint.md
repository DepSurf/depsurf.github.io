# Function: <code>__snbep_cbox_get_constraint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578949200,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:724",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949200,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946048,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:724",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946048,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946512,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:795",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946512,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578939488,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:794",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939488,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578941504,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:795",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578941504,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578943968,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:795",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943968,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945968,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:795",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945968,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951760,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:863",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951760,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954192,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:858",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954192,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578961200,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:895",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961200,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962480,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:924",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962480,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967776,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:924",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967776,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:944",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986384,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071592045602,
      "name": "__snbep_cbox_get_constraint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578994064,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:944",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994064,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579014992,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:946",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014992,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579015040,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:946",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015040,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579039968,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:946",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039968,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954192,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:858",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954192,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951792,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:858",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951792,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954128,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:858",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954128,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```

```json
{
  "name": "__snbep_cbox_get_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954704,
      "name": "__snbep_cbox_get_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:858",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:knl_cha_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_get_constraint",
        "arch/x86/events/intel/uncore_snbep.c:snbep_cbox_get_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954704,
      "name": "__snbep_cbox_get_constraint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct event_constraint * __snbep_cbox_get_constraint(struct intel_uncore_box * box, struct perf_event * event, u64 (*)(int) cbox_filter_mask)
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
