# Function: <code>parse_expr</code>

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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580551984,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2688",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551984,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607088,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2804",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607088,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664368,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2961",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664368,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580711568,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711568,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834320,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2169",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834320,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824640,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2179",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824640,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830064,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2222",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830064,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027216,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2275",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027216,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1431
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int * n_subexprs)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276880,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2588",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276880,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2039
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int * n_subexprs)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601248,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2638",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601248,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int * n_subexprs)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723088,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2660",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723088,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2026
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int * n_subexprs)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839408,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2653",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839408,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2026
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492023088,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492023088,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285184656,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285184656,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1564
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680368,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680368,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626576,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626576,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580671616,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671616,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
```

```json
{
  "name": "parse_expr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729120,
      "name": "parse_expr",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3074",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729120,
      "name": "parse_expr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int * n_subexprs</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int level</code>
</li>
</ul>
</details>
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
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
struct hist_field * parse_expr(struct hist_trigger_data * hist_data, struct trace_event_file * file, char * str, long unsigned int flags, char * var_name, unsigned int level)
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
