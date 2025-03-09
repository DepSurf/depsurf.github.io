# Function: <code>trace_inject_entry</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801488,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
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
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580789456,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
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
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580794944,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
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
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580989296,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
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
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581235330,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int trace_inject_entry(struct trace_event_file * file, void * rec, int len)
```

```json
{
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555072,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555072,
      "name": "trace_inject_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int trace_inject_entry(struct trace_event_file * file, void * rec, int len)
```

```json
{
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673616,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673616,
      "name": "trace_inject_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int trace_inject_entry(struct trace_event_file * file, void * rec, int len)
```

```json
{
  "name": "trace_inject_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789760,
      "name": "trace_inject_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:17",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789760,
      "name": "trace_inject_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int trace_inject_entry(struct trace_event_file * file, void * rec, int len)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
