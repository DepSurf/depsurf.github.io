# Function: <code>parse_synth_field</code>

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
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580564765,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:750",
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
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580611385,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:813",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:967",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674880,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1270
    },
    {
      "addr": 18446744071580684040,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722016,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071580731051,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808256,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:462",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808256,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799024,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:582",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799024,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803984,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:600",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803984,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580998672,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:600",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998672,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245312,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:608",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245312,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1441
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567824,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:619",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567824,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687056,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:688",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687056,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1725
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
struct synth_field * parse_synth_field(int argc, char * * argv, int * consumed, int * field_version)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803392,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:689",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803392,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1682
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492038408,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492038408,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285192304,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285192304,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5024
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690816,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071580699851,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637024,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071580646059,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682064,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071580691099,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```

```json
{
  "name": "parse_synth_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_synth_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1037",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739568,
      "name": "parse_synth_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071580748603,
      "name": "parse_synth_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * field_version</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char * * argv</code> ➡️ <code>char * * argv</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct synth_field * parse_synth_field(int argc, const char * * argv, int * consumed)
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
