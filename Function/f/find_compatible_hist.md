# Function: <code>find_compatible_hist</code>

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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580561377,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2842",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580621646,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2958",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580679366,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3115",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580726550,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
struct hist_trigger_data * find_compatible_hist(struct hist_trigger_data * target_hist_data, struct trace_event_file * file)
```

```json
{
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815696,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2325",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815696,
      "name": "find_compatible_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
struct hist_trigger_data * find_compatible_hist(struct hist_trigger_data * target_hist_data, struct trace_event_file * file)
```

```json
{
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805904,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2335",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805904,
      "name": "find_compatible_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580836455,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2392",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581036839,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2446",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581291786,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2823",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581616586,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2874",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581739177,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2896",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581856089,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2889",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492034412,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285201676,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580695350,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580641558,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686598,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
  "name": "find_compatible_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580744102,
      "name": "find_compatible_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
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
struct hist_trigger_data * find_compatible_hist(struct hist_trigger_data * target_hist_data, struct trace_event_file * file)
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
struct hist_trigger_data * find_compatible_hist(struct hist_trigger_data * target_hist_data, struct trace_event_file * file)
```
</details>
</li>
</ul>
