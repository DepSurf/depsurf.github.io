# Function: <code>__perf_remove_from_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __perf_remove_from_context(void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403920,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403920,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477184,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1861",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477184,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541264,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1873",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541264,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580570752,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1886",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570752,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645872,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1871",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645872,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773792,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2068",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773792,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840384,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2068",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840384,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936176,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2070",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936176,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017504,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017504,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198640,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2300",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198640,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240608,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2340",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240608,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581255520,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2344",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255520,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499808,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2412",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499808,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845984,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845984,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272896,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2310",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272896,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473776,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2310",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473776,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642480,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2348",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642480,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492370536,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492370536,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226255360,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226255360,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285625168,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285625168,
      "name": "__perf_remove_from_context",
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272482056,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272482056,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986352,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986352,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932560,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932560,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977552,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977552,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void __perf_remove_from_context(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038368,
      "name": "__perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2155",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_exit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038368,
      "name": "__perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event * event</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_cpu_context * cpuctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_event_context * ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>info</code> ➡️ <code>event, cpuctx, ctx, info</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
