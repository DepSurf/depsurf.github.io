# Function: <code>__release_bp_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445136,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:327",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445136,
      "name": "__release_bp_slot",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520080,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:327",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520080,
      "name": "__release_bp_slot",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584048,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:327",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584048,
      "name": "__release_bp_slot",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614688,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:327",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614688,
      "name": "__release_bp_slot",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695360,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:327",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695360,
      "name": "__release_bp_slot",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580826992,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:328",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826992,
      "name": "__release_bp_slot.isra.12",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893728,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:328",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893728,
      "name": "__release_bp_slot.isra.13",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991248,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991248,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581045232,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045232,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581226452,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:329",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581269028,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:329",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581287684,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:329",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581532020,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:329",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581880239,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:329",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582312409,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:632",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582513513,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:632",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582680627,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:607",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:bp_perf_event_destroy",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492401864,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492401864,
      "name": "__release_bp_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226286812,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226286812,
      "name": "__release_bp_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285664800,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285664800,
      "name": "__release_bp_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014080,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014080,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580960208,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960208,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581005280,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005280,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_bp_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066480,
      "name": "__release_bp_slot",
      "external": false,
      "loc": "kernel/events/hw_breakpoint.c:315",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:release_bp_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066480,
      "name": "__release_bp_slot.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void __release_bp_slot(struct perf_event * bp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void __release_bp_slot(struct perf_event * bp, u64 bp_type)
```
</details>
</li>
</ul>
