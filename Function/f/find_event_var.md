# Function: <code>find_event_var</code>

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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546096,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1584",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546096,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605216,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1668",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605216,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662384,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1823",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662384,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709568,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709568,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826896,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:992",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826896,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817152,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:995",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817152,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823840,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1011",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823840,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020560,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1035",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020560,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271360,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1209",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271360,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 843
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595536,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1242",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595536,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 843
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718496,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1239",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718496,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834768,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1232",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834768,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492021176,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492021176,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285164816,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285164816,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580678368,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678368,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624576,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624576,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669616,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669616,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_event_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727120,
      "name": "find_event_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1901",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727120,
      "name": "find_event_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hist_field * find_event_var(struct hist_trigger_data * hist_data, char * system, char * event_name, char * var_name)
```
</details>
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
