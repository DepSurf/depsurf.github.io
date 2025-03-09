# Function: <code>set_synth_event_print_fmt</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580566233,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:723",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580613061,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:786",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580683039,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:940",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580730319,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call * call)
```

```json
{
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804384,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:435",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804384,
      "name": "set_synth_event_print_fmt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call * call)
```

```json
{
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793088,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:555",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793088,
      "name": "set_synth_event_print_fmt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580802076,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:556",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580996684,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:556",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581243347,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:564",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581563323,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:575",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581682475,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:644",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581798969,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:645",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:register_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492040364,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285207976,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580699119,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580645327,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580690367,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
  "name": "set_synth_event_print_fmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580747871,
      "name": "set_synth_event_print_fmt",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1010",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call * call)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call * call)
```
</details>
</li>
</ul>
