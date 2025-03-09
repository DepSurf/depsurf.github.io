# Function: <code>__create_val_field</code>

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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553104,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3831",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553104,
      "name": "__create_val_field",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608240,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3916",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608240,
      "name": "__create_val_field",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4386",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665584,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580683864,
      "name": "__create_val_field.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712784,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712784,
      "name": "__create_val_field",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835616,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3610",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835616,
      "name": "__create_val_field",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825936,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825936,
      "name": "__create_val_field",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831344,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3697",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831344,
      "name": "__create_val_field",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581031105,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:3754",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:create_var_field"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278928,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4131",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278928,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603312,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4187",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603312,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725136,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4230",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725136,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841456,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4223",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841456,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492024216,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492024216,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285186224,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285186224,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681584,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681584,
      "name": "__create_val_field",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627792,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627792,
      "name": "__create_val_field",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672832,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672832,
      "name": "__create_val_field",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```

```json
{
  "name": "__create_val_field",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730336,
      "name": "__create_val_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4508",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730336,
      "name": "__create_val_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
```
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
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
int __create_val_field(struct hist_trigger_data * hist_data, unsigned int val_idx, struct trace_event_file * file, char * var_name, char * field_str, long unsigned int flags)
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
