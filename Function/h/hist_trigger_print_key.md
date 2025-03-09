# Function: <code>hist_trigger_print_key</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667584,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5307",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667584,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580713568,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713568,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820816,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4525",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "kernel/trace/trace_events_hist.c:track_data_snapshot_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820816,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811632,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4566",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "kernel/trace/trace_events_hist.c:track_data_snapshot_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811632,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815984,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4635",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815984,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012640,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4733",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012640,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259728,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5111",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259728,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579616,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5245",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579616,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700304,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5343",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700304,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
```

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816608,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5335",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:print_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816608,
      "name": "hist_trigger_print_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492026200,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492026200,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    }
  ]
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
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285165792,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285165792,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
    }
  ]
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
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682368,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682368,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628576,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628576,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673616,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673616,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_trigger_print_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580731120,
      "name": "hist_trigger_print_key",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_show",
        "kernel/trace/trace_events_hist.c:hist_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731120,
      "name": "hist_trigger_print_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void hist_trigger_print_key(struct seq_file * m, struct hist_trigger_data * hist_data, void * key, struct tracing_map_elt * elt)
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
