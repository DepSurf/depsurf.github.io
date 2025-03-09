# Function: <code>perf_group_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580392338,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1368",
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
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580467268,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1621",
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
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580529959,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1627",
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
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580561595,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1640",
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635952,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1639",
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
      "addr": 18446744071580635952,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762592,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1821",
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
      "addr": 18446744071580762592,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829392,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1821",
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
      "addr": 18446744071580829392,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924384,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446744071580924384,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978272,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446744071580978272,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150368,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1950",
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
      "addr": 18446744071581150368,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190240,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1974",
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
      "addr": 18446744071581190240,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209872,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1957",
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
      "addr": 18446744071581209872,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450080,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:2025",
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
      "addr": 18446744071581450080,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793520,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1936",
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
      "addr": 18446744071581793520,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226400,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1938",
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
      "addr": 18446744071582226400,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582427296,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1938",
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
      "addr": 18446744071582427296,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573488,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1974",
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
      "addr": 18446744071582573488,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492328064,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446603336492328064,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226208468,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 3226208468,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285563856,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 13835058055285563856,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272447742,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446743936272447742,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947072,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446744071580947072,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893136,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446744071580893136,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938320,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
```

```json
{
  "name": "perf_group_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999904,
      "name": "perf_group_attach",
      "external": false,
      "loc": "kernel/events/core.c:1823",
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
      "addr": 18446744071580999904,
      "name": "perf_group_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void perf_group_attach(struct perf_event * event)
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
