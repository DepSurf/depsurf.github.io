# Function: <code>onmatch_destroy</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void onmatch_destroy(struct action_data * data)
```

```json
{
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533360,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3481",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533360,
      "name": "onmatch_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void onmatch_destroy(struct action_data * data)
```

```json
{
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591552,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3588",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591552,
      "name": "onmatch_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580672712,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4018",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580720138,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831706,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3231",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580822026,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3241",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580826002,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3307",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581023148,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3363",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581267834,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3740",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581591802,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3792",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581713786,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3830",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581829738,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3823",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:onmatch_parse"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492030224,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285190972,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580688938,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580635146,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580680186,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
  "name": "onmatch_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580737690,
      "name": "onmatch_destroy",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4135",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void onmatch_destroy(struct action_data * data)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void onmatch_destroy(struct action_data * data)
```
</details>
</li>
</ul>
