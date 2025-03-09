# Function: <code>__add_hash_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580156828,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1249",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:add_hash_entry",
        "kernel/trace/ftrace.c:ftrace_hash_move"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190336,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1218",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190336,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230960,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1224",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230960,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240592,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1249",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240592,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291840,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1225",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291840,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353088,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1214",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353088,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409328,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1163",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409328,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462304,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1160",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462304,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511184,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511184,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580605818,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1149",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597968,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580595849,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1148",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587920,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580598552,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1148",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590912,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580769794,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1149",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762528,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071592165449,
      "name": "__add_hash_entry.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580987394,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1143",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:ftrace_add_rec_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978672,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071593938834,
      "name": "__add_hash_entry.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284674,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1143",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:ftrace_add_rec_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275120,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071596001925,
      "name": "__add_hash_entry.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581379938,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1174",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:dup_hash"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_set_hash",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:match_records",
        "kernel/trace/ftrace.c:match_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370480,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071596520486,
      "name": "__add_hash_entry.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581487311,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1174",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:__ftrace_hash_move"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477600,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071597420871,
      "name": "__add_hash_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491790784,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491790784,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225762816,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284840592,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284840592,
      "name": "__add_hash_entry",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272104638,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272104638,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479984,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479984,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427056,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427056,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471232,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471232,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```

```json
{
  "name": "__add_hash_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527392,
      "name": "__add_hash_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_func_mapper_add_ip",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:__ftrace_hash_move",
        "kernel/trace/ftrace.c:add_hash_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527392,
      "name": "__add_hash_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __add_hash_entry(struct ftrace_hash * hash, struct ftrace_func_entry * entry)
```
</details>
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
