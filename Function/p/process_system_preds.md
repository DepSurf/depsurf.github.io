# Function: <code>process_system_preds</code>

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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580524666,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1573",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582470,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1566",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580639569,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1588",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686305,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790544,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790544,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580778560,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1569",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778560,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783840,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1569",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783840,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968944,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1662",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968944,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212800,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1690",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212800,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530688,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1787",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530688,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649920,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1878",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649920,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
```

```json
{
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765776,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:2139",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765776,
      "name": "process_system_preds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491994864,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225930040,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285121032,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272261084,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580655105,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580601313,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580646353,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
  "name": "process_system_preds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580703857,
      "name": "process_system_preds",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1590",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
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
int process_system_preds(struct trace_subsystem_dir * dir, struct trace_array * tr, struct filter_parse_error * pe, char * filter_string)
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
