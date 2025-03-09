# Function: <code>create_var_ref</code>

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
struct hist_field * create_var_ref(struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580550464,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2346",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550464,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599664,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2459",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599664,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657584,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2613",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657584,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704304,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704304,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833472,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1808",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833472,
      "name": "create_var_ref",
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823792,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1818",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823792,
      "name": "create_var_ref",
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827184,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1844",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827184,
      "name": "create_var_ref",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025088,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1878",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025088,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271008,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2136",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271008,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595136,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2174",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595136,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717200,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2188",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717200,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833376,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2181",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833376,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492016096,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492016096,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285177872,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285177872,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673104,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673104,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580619312,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619312,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664352,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664352,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
```

```json
{
  "name": "create_var_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721856,
      "name": "create_var_ref",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721856,
      "name": "create_var_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct hist_field * create_var_ref(struct hist_field * var_field, char * system, char * event_name)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hist_trigger_data * hist_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>var_field, system, event_name</code> ➡️ <code>hist_data, var_field, system, event_name</code>
</li>
</ul>
</details>
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
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
struct hist_field * create_var_ref(struct hist_trigger_data * hist_data, struct hist_field * var_field, char * system, char * event_name)
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
