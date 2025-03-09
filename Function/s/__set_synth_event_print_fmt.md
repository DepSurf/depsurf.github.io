# Function: <code>__set_synth_event_print_fmt</code>

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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545584,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:693",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/trace/trace_events_hist.c:create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545584,
      "name": "__set_synth_event_print_fmt.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580602608,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:756",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602608,
      "name": "__set_synth_event_print_fmt.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580660608,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:910",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660608,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580707792,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707792,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804048,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:405",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:set_synth_event_print_fmt",
        "kernel/trace/trace_events_synth.c:set_synth_event_print_fmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804048,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792704,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:520",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:set_synth_event_print_fmt",
        "kernel/trace/trace_events_synth.c:set_synth_event_print_fmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792704,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798304,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:521",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798304,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:521",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992848,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071592176679,
      "name": "__set_synth_event_print_fmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:529",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242256,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071593950598,
      "name": "__set_synth_event_print_fmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:540",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562192,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071596009100,
      "name": "__set_synth_event_print_fmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:606",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681296,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071596527958,
      "name": "__set_synth_event_print_fmt.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
```

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:607",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event",
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797440,
      "name": "__set_synth_event_print_fmt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071597428570,
      "name": "__set_synth_event_print_fmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492019384,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492019384,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285160384,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285160384,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580676592,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580676592,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622800,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622800,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667840,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667840,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "__set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580725344,
      "name": "__set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:980",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725344,
      "name": "__set_synth_event_print_fmt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __set_synth_event_print_fmt(struct synth_event * event, char * buf, int len)
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
