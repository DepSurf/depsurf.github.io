# Function: <code>ftrace_lookup_ip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155792,
      "name": "ftrace_lookup_ip",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1226",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:t_next",
        "kernel/trace/ftrace.c:t_next",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155792,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190240,
      "name": "ftrace_lookup_ip",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1195",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:t_next",
        "kernel/trace/ftrace.c:t_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190240,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230864,
      "name": "ftrace_lookup_ip",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1201",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:t_next",
        "kernel/trace/ftrace.c:t_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230864,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248688,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1241",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:ftrace_push_return_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248688,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580300768,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1217",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:ftrace_push_return_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300768,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361744,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1206",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:ftrace_push_return_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361744,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417664,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1155",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417664,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471200,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1152",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471200,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519344,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519344,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608880,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1141",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_func_from_hashes",
        "kernel/trace/ftrace.c:clear_func_from_hashes",
        "kernel/trace/ftrace.c:referenced_filters",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608880,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598992,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1140",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:clear_func_from_hashes",
        "kernel/trace/ftrace.c:clear_func_from_hashes",
        "kernel/trace/ftrace.c:referenced_filters",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598992,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601872,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1140",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:referenced_filters",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601872,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1141",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:referenced_filters",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592166376,
      "name": "ftrace_lookup_ip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580772976,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1135",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:referenced_filters",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593939878,
      "name": "ftrace_lookup_ip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580991248,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1135",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596002686,
      "name": "ftrace_lookup_ip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581288944,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1166",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521132,
      "name": "ftrace_lookup_ip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581383952,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1166",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ops_references_ip",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:enter_record",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597421597,
      "name": "ftrace_lookup_ip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581491808,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491799928,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491799928,
      "name": "ftrace_lookup_ip",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225747640,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:t_func_next",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225747640,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284854768,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:t_func_next",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284854768,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272112426,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/ftrace.c:t_func_next",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272112426,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580488144,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488144,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435168,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435168,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479392,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479392,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct ftrace_func_entry * ftrace_lookup_ip(struct ftrace_hash * hash, long unsigned int ip)
```

```json
{
  "name": "ftrace_lookup_ip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535632,
      "name": "ftrace_lookup_ip",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1153",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_module_enable",
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:ftrace_func_mapper_find_ip",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535632,
      "name": "ftrace_lookup_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
