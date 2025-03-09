# Function: <code>create_field_var_hist</code>

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
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580561314,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2922",
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
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580621583,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3038",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679264,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3195",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679264,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726448,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726448,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840544,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2407",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840544,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830752,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2417",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830752,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836352,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2474",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836352,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036736,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2528",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036736,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2905",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291680,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1834
    },
    {
      "addr": 18446744071593951889,
      "name": "create_field_var_hist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616480,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2956",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616480,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1845
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739072,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2978",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739072,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2432
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855984,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2971",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855984,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2526
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492034328,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492034328,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285201552,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285201552,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2052
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695248,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695248,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641456,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641456,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686496,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686496,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```

```json
{
  "name": "create_field_var_hist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580744000,
      "name": "create_field_var_hist",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:trace_action_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580744000,
      "name": "create_field_var_hist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
```
</details>
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
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
struct hist_field * create_field_var_hist(struct hist_trigger_data * target_hist_data, char * subsys_name, char * event_name, char * field_name)
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
