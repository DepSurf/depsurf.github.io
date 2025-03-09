# Function: <code>find_synth_event</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535632,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:860",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/trace/trace_events_hist.c:create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535632,
      "name": "find_synth_event",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580593968,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:946",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580593968,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651440,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1100",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651440,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698000,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698000,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580810387,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:568",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811136,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580800395,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:730",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801392,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805294,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:748",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807152,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580999982,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:748",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001968,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581246961,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:756",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249280,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581567576,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:767",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_delete",
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571872,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581685928,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:839",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_delete",
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691856,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802264,
      "name": "find_synth_event",
      "external": true,
      "loc": "kernel/trace/trace_events_synth.c:840",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_delete",
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808160,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492007720,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492007720,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285142320,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285142320,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666800,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666800,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613008,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613008,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658048,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658048,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct synth_event * find_synth_event(const char * name)
```

```json
{
  "name": "find_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715552,
      "name": "find_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1170",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715552,
      "name": "find_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct synth_event * find_synth_event(const char * name)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct synth_event * find_synth_event(const char * name)
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
struct synth_event * find_synth_event(const char * name)
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
