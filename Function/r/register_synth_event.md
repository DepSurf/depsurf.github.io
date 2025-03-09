# Function: <code>register_synth_event</code>

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
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565919,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:872",
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
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580612757,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:962",
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
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682751,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1116",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580730031,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:590",
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
      "addr": 18446744071580807072,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071580811236,
      "name": "register_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:752",
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
      "addr": 18446744071580797280,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071591322403,
      "name": "register_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:770",
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
      "addr": 18446744071580801776,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071591264222,
      "name": "register_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:770",
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
      "addr": 18446744071580996384,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071592177036,
      "name": "register_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:778",
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
      "addr": 18446744071581243040,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
    },
    {
      "addr": 18446744071593950672,
      "name": "register_synth_event.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563024,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:789",
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
      "addr": 18446744071581563024,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682176,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:861",
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
      "addr": 18446744071581682176,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int register_synth_event(struct synth_event * event)
```

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798624,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:862",
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
      "addr": 18446744071581798624,
      "name": "register_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492040140,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285207720,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580698831,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580645039,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580690079,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580747583,
      "name": "register_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1186",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int register_synth_event(struct synth_event * event)
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
