# Function: <code>filter_parse_regex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302592,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:364",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_set_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306800,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580345212,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:364",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_set_func",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349840,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580393728,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:386",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_set_func",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:register_ftrace_function_probe",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393728,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405120,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:386",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405120,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460560,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:386",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460560,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518992,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:823",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518992,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576656,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:812",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576656,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633904,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:819",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633904,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680560,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680560,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580786416,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786416,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774384,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774384,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779232,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779232,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963680,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:892",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963680,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207104,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:915",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:filter_build_regex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207104,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581525200,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:950",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:filter_build_regex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525200,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643808,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:964",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:filter_build_regex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643808,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758832,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1083",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:filter_build_regex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758832,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491988872,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491988872,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225923700,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225923700,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285112432,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285112432,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272256346,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272256346,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649360,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649360,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595568,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595568,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640608,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640608,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
enum regex_type filter_parse_regex(char * buff, int len, char * * search, int * not)
```

```json
{
  "name": "filter_parse_regex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698112,
      "name": "filter_parse_regex",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:821",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698112,
      "name": "filter_parse_regex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
