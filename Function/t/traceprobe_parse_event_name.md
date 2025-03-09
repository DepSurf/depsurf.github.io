# Function: <code>traceprobe_parse_event_name</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663570,
      "name": "traceprobe_parse_event_name.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580662256,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580725696,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:219",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725696,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774608,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774608,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891632,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891632,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885920,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885920,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889648,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889648,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091024,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091024,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352752,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352752,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687280,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:236",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687280,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830720,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:240",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830720,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953408,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:241",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953408,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492086144,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492086144,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225986344,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225986344,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285280016,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285280016,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743408,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743408,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689600,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689600,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734656,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734656,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
```

```json
{
  "name": "traceprobe_parse_event_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792608,
      "name": "traceprobe_parse_event_name",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:229",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792608,
      "name": "traceprobe_parse_event_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offset</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int traceprobe_parse_event_name(const char * * pevent, const char * * pgroup, char * buf, int offset)
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
