# Function: <code>list_add_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580392233,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1216",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:add_event_to_ctx"
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
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580467113,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1467",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:add_event_to_ctx"
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
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580529785,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1475",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:add_event_to_ctx"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580561393,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1488",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:add_event_to_ctx"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643744,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1482",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643744,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580775392,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1668",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775392,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842000,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1668",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842000,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938320,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938320,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991168,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991168,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144368,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1793",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144368,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184416,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1811",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184416,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202784,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1794",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202784,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442480,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1862",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442480,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783808,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1771",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783808,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211792,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1769",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211792,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411808,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1769",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411808,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579584,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1780",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579584,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492351496,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492351496,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226214712,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226214712,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285568272,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285568272,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272449058,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272449058,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959968,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959968,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906096,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906096,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951216,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951216,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "list_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014784,
      "name": "list_add_event",
      "external": false,
      "loc": "kernel/events/core.c:1670",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014784,
      "name": "list_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void list_add_event(struct perf_event * event, struct perf_event_context * ctx)
```
</details>
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
