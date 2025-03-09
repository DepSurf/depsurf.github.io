# Function: <code>perf_event_set_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423856,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:8132",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423856,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497056,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:9260",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497056,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560512,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:9467",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560512,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580590736,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:9690",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590736,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580670848,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:9717",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670848,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802496,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10246",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802496,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869056,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10289",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869056,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965888,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10636",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965888,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020048,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020048,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581205645,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:11332",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200544,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581247970,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:11616",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242528,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264999,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:11783",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259360,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581518638,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:11895",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495920,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581865932,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:11843",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848832,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293284,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:12140",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275696,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582494008,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:12180",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476576,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582662456,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:12264",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645168,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492372832,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492372832,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226258148,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226258148,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285628400,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285628400,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272457976,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272457976,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988896,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988896,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935088,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935088,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980096,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980096,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int perf_event_set_output(struct perf_event * event, struct perf_event * output_event)
```

```json
{
  "name": "perf_event_set_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040928,
      "name": "perf_event_set_output",
      "external": false,
      "loc": "kernel/events/core.c:10737",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040928,
      "name": "perf_event_set_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
