# Function: <code>__free_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __free_filter(struct event_filter * filter)
```

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580300080,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:837",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:free_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300080,
      "name": "__free_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __free_filter(struct event_filter * filter)
```

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343008,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:834",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343008,
      "name": "__free_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __free_filter(struct event_filter * filter)
```

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389808,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:865",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389808,
      "name": "__free_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580410524,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:865",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402816,
      "name": "__free_filter.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580465964,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:864",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458256,
      "name": "__free_filter.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525526,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1019",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518208,
      "name": "__free_filter.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580583366,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1009",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575872,
      "name": "__free_filter.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640502,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1028",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633024,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687238,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679664,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580792821,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786064,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780837,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774032,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580786134,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778880,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580971430,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1101",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963232,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581215477,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1124",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206592,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533508,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1172",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522128,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581652741,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1186",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641120,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581768757,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1305",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755584,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491995680,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491987888,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225930960,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225923172,
      "name": "__free_filter.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285122204,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285110672,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272261838,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272255398,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580656038,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648464,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580602246,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594672,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580647286,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639712,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "__free_filter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580704790,
      "name": "__free_filter",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1030",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_events_filter.c:ftrace_profile_free_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter_start",
        "kernel/trace/trace_events_filter.c:free_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697216,
      "name": "__free_filter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __free_filter(struct event_filter * filter)
```
</details>
</li>
</ul>
