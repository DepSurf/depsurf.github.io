# Function: <code>add_event_to_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_event_to_ctx(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580392176,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2039",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580392176,
      "name": "add_event_to_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
void add_event_to_ctx(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580467056,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2174",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467056,
      "name": "add_event_to_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
void add_event_to_ctx(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529728,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2212",
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
      "addr": 18446744071580529728,
      "name": "add_event_to_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void add_event_to_ctx(struct perf_event * event, struct perf_event_context * ctx)
```

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580561344,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2252",
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
      "addr": 18446744071580561344,
      "name": "add_event_to_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580659645,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2194",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790189,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2391",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856237,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2391",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580954373,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2394",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581007285,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581188409,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2628",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581230040,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2663",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581246712,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2665",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581480102,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2704",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581794132,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2617",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582227079,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2618",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582427975,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2618",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582580423,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2656",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492352288,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226218636,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285598768,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272471648,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580976085,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580918409,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580967333,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_event_to_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581015491,
      "name": "add_event_to_ctx",
      "external": false,
      "loc": "kernel/events/core.c:2479",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context"
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void add_event_to_ctx(struct perf_event * event, struct perf_event_context * ctx)
```
</details>
</li>
</ul>
