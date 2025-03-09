# Function: <code>free_ftrace_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_ftrace_hash(struct ftrace_hash * hash)
```

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156928,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1315",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:register_ftrace_function_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156928,
      "name": "free_ftrace_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void free_ftrace_hash(struct ftrace_hash * hash)
```

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191392,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1284",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191392,
      "name": "free_ftrace_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void free_ftrace_hash(struct ftrace_hash * hash)
```

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232016,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1290",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232016,
      "name": "free_ftrace_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261781,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1333",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245536,
      "name": "free_ftrace_hash.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580313749,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1309",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297408,
      "name": "free_ftrace_hash.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580374421,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1298",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358544,
      "name": "free_ftrace_hash.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430805,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1247",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414208,
      "name": "free_ftrace_hash.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580483403,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1244",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467152,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071580491613,
      "name": "free_ftrace_hash.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580532518,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515952,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580625106,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1233",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605408,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580615490,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1232",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595440,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580617810,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1232",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598128,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789458,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1233",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769232,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071592166096,
      "name": "free_ftrace_hash.part.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581010422,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1227",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986864,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071593939617,
      "name": "free_ftrace_hash.part.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581310582,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1227",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_destroy_filter_files",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283296,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071596002425,
      "name": "free_ftrace_hash.part.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581402936,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1258",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378464,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071596520888,
      "name": "free_ftrace_hash.part.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581510558,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1259",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485392,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071597421199,
      "name": "free_ftrace_hash.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491814288,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491795768,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225762556,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225744268,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284875912,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284849184,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272124894,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272109844,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580501318,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484752,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580448342,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432416,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580492566,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476000,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "free_ftrace_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548774,
      "name": "free_ftrace_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1245",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:free_ftrace_func_mapper",
        "kernel/trace/ftrace.c:process_mod_list",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:ftrace_free_filter",
        "kernel/trace/ftrace.c:__free_ftrace_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532208,
      "name": "free_ftrace_hash.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void free_ftrace_hash(struct ftrace_hash * hash)
```
</details>
</li>
</ul>
