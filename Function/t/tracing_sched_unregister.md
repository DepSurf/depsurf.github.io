# Function: <code>tracing_sched_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580247865,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:71",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580290985,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:71",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580334601,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:71",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347040,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:82",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347040,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400528,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400528,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462208,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462208,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517856,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517856,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580574064,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574064,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621152,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621152,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580720389,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580709829,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580714213,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580892853,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581128353,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:84",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581439025,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:84",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581535857,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:84",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581648001,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:84",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491923272,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491923272,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225859048,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225859048,
      "name": "tracing_sched_unregister",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285018992,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285018992,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272201612,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272201612,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589952,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589952,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536576,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536576,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581200,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581200,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
```

```json
{
  "name": "tracing_sched_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637936,
      "name": "tracing_sched_unregister",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:83",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637936,
      "name": "tracing_sched_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void tracing_sched_unregister()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tracing_sched_unregister()
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
