# Function: <code>err_pos</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:6962",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556177,
      "name": "err_pos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580551328,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598992,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598992,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699264,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7208",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699264,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690048,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7282",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_var_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690048,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694256,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7618",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694256,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870816,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7782",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_var_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:track_data_create",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870816,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101072,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7811",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101072,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408960,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7865",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408960,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503936,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:8028",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503936,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615376,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:8064",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:__create_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615376,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491897536,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491897536,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225839864,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225839864,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284983616,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284983616,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272185900,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272185900,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567792,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567792,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514464,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514464,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559040,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559040,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int err_pos(char * cmd, const char * str)
```

```json
{
  "name": "err_pos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615760,
      "name": "err_pos",
      "external": true,
      "loc": "kernel/trace/trace.c:7012",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:create_hist_fields",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615760,
      "name": "err_pos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int err_pos(char * cmd, const char * str)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
