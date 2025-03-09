# Function: <code>parse_entry</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800672,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:192",
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
      "addr": 18446744071580800672,
      "name": "parse_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788640,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:192",
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
      "addr": 18446744071580788640,
      "name": "parse_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794096,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:192",
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
      "addr": 18446744071580794096,
      "name": "parse_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988448,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:192",
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
      "addr": 18446744071580988448,
      "name": "parse_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581234432,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:196",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234432,
      "name": "parse_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581555568,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:196",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555568,
      "name": "parse_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674112,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:196",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674112,
      "name": "parse_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790256,
      "name": "parse_entry",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:196",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:event_inject_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790256,
      "name": "parse_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int parse_entry(char * str, struct trace_event_call * call, void * * pentry)
```
</details>
</li>
</ul>
