# Function: <code>_perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580408688,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1778",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408688,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483152,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1934",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483152,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548544,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1966",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548544,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580320,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1979",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580320,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660048,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1972",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660048,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790896,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2169",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790896,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857264,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2169",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857264,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950112,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2171",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950112,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003024,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003024,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174720,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2403",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174720,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215552,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2443",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215552,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237152,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2445",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237152,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475584,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2520",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475584,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829486,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2433",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801200,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582256910,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2438",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230720,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457502,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2438",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431136,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582626318,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2476",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_event_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598176,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492354312,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492354312,
      "name": "_perf_event_disable",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226209984,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226209984,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285595520,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285595520,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272469014,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272469014,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971824,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971824,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917584,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917584,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963072,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963072,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void _perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "_perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993824,
      "name": "_perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2256",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993824,
      "name": "_perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
