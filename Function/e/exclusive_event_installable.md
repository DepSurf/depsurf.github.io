# Function: <code>exclusive_event_installable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580393376,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:3675",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393376,
      "name": "exclusive_event_installable.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580453328,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:3946",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453328,
      "name": "exclusive_event_installable",
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515760,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4043",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515760,
      "name": "exclusive_event_installable",
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547280,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4130",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547280,
      "name": "exclusive_event_installable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627520,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4064",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627520,
      "name": "exclusive_event_installable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756400,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4399",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756400,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822704,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4400",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822704,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917328,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4424",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917328,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970784,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970784,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140016,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4745",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140016,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180048,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180048,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198528,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4908",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198528,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438880,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:5014",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438880,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778864,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4912",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778864,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203792,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:5124",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203792,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403840,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:5124",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403840,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571728,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:5173",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571728,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492321784,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492321784,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226206360,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226206360,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285561664,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285561664,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272446810,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272446810,
      "name": "exclusive_event_installable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939584,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939584,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885648,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885648,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930832,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930832,
      "name": "exclusive_event_installable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "exclusive_event_installable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991600,
      "name": "exclusive_event_installable",
      "external": false,
      "loc": "kernel/events/core.c:4519",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991600,
      "name": "exclusive_event_installable",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool exclusive_event_installable(struct perf_event * event, struct perf_event_context * ctx)
```
</details>
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
