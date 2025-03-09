# Function: <code>synth_field_size</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580564948,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:504",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_synth_event"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580611758,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:567",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580675265,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:721",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580722411,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805216,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:155",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_check_arg_fn",
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805216,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071580805712,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580794032,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:200",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_check_arg_fn",
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794032,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    },
    {
      "addr": 18446744071580794560,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580799488,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:201",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_check_arg_fn",
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799488,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071580799920,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580994112,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:201",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_check_arg_fn",
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994112,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071580994544,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241472,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:209",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241472,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071581241904,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581561328,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:211",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561328,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071581561776,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581680240,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:230",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680240,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071581680688,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int synth_field_size(char * type)
```

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796384,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:230",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:parse_synth_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796384,
      "name": "synth_field_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071581796832,
      "name": "synth_field_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492038780,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285193124,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580691211,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637419,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682459,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synth_field_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580739963,
      "name": "synth_field_size",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:730",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_synth_field"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int synth_field_size(char * type)
```
</details>
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
