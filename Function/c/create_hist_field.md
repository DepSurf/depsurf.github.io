# Function: <code>create_hist_field</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_hist_field(struct ftrace_event_field * field, long unsigned int flags)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364640,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:347",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364640,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct hist_field * create_hist_field(struct ftrace_event_field * field, long unsigned int flags)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411744,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:347",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411744,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_hist_field(struct ftrace_event_field * field, long unsigned int flags)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422992,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:348",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422992,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_hist_field(struct ftrace_event_field * field, long unsigned int flags)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478624,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:385",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478624,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549696,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2164",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549696,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598880,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2256",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598880,
      "name": "create_hist_field",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656832,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2410",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656832,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703520,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703520,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837160,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1587",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830096,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580827304,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1597",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820416,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832510,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1621",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827472,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581030198,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1659",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025440,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284825,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1903",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272576,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581606218,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1939",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596800,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581725552,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1946",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717600,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581833527,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1939",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_var_ref"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833824,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492015336,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492015336,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285176864,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285176864,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672320,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672320,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618528,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618528,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580663568,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663568,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
```

```json
{
  "name": "create_hist_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721072,
      "name": "create_hist_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2492",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:create_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721072,
      "name": "create_hist_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct hist_field * create_hist_field(struct ftrace_event_field * field, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hist_trigger_data * hist_data</code>
</li>
<li>
<b>Param added. </b>
<code>char * var_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>field, flags</code> ➡️ <code>hist_data, field, flags, var_name</code>
</li>
</ul>
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
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
struct hist_field * create_hist_field(struct hist_trigger_data * hist_data, struct ftrace_event_field * field, long unsigned int flags, char * var_name)
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
