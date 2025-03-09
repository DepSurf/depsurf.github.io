# Function: <code>hist_err</code>

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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580557538,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:367",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:hist_err_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:hist_err_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537184,
      "name": "hist_err.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071580566758,
      "name": "hist_err.part.10.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580619537,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:433",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:hist_err_event"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:create_field_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:hist_err_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595616,
      "name": "hist_err.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071580624408,
      "name": "hist_err.part.11.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580678726,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:622",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580725910,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580832577,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:568",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
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
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_match_var"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580822897,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:571",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
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
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_match_var"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580826881,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:584",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
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
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581024289,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:608",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:track_data_create",
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
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_field",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hist_err(struct trace_array * tr, u8 err_type, u16 err_pos)
```

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581282634,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:778",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254144,
      "name": "hist_err",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hist_err(struct trace_array * tr, u8 err_type, u16 err_pos)
```

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581607642,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:811",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574464,
      "name": "hist_err",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hist_err(struct trace_array * tr, u8 err_type, u16 err_pos)
```

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581730105,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:808",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695152,
      "name": "hist_err",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hist_err(struct trace_array * tr, u8 err_type, u16 err_pos)
```

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846409,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:801",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_actions",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:create_sort_keys",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:parse_var_defs",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_val_fields",
        "kernel/trace/trace_events_hist.c:__create_val_field",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_assignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811456,
      "name": "hist_err",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492033648,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285200596,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_atom",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580694710,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580640918,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580685958,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
  "name": "hist_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743462,
      "name": "hist_err",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:629",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
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
        "kernel/trace/trace_events_hist.c:action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:action_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_action_params",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void hist_err(struct trace_array * tr, u8 err_type, u16 err_pos)
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
