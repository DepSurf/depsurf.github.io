# Function: <code>__perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __perf_event_disable(void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403632,
      "name": "__perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:1727",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pending_event",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403632,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580476560,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1902",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476560,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580540640,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1934",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540640,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571792,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1947",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571792,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580647088,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:1937",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647088,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776704,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2134",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776704,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844928,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2134",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844928,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941456,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2136",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941456,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995056,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995056,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164160,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2367",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164160,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203888,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2407",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203888,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581227840,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2409",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227840,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463264,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2484",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463264,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809680,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2397",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809680,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247488,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2398",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247488,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448192,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2398",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448192,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617344,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2436",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617344,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492356736,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492356736,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226240800,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226240800,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285606544,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285606544,
      "name": "__perf_event_disable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272482420,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272482420,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963856,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963856,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909984,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909984,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955104,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955104,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __perf_event_disable(struct perf_event * event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx, void * info)
```

```json
{
  "name": "__perf_event_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019568,
      "name": "__perf_event_disable",
      "external": false,
      "loc": "kernel/events/core.c:2221",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019568,
      "name": "__perf_event_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
