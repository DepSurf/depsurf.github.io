# Function: <code>tracing_start_sched_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580247617,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:78",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580290737,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:78",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580334353,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:78",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346704,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:89",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346704,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400192,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400192,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461936,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071580462472,
      "name": "tracing_start_sched_switch.cold.0",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517584,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071580518120,
      "name": "tracing_start_sched_switch.cold.0",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573760,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071580574328,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620912,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580621416,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580720032,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720032,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709472,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709472,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713776,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071591262609,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892416,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071592172677,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:91",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127840,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071593946277,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438384,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:91",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438384,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535216,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:91",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535216,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647360,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:91",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647360,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491922920,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491922920,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225858744,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225858744,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285018464,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285018464,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272201290,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272201290,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589712,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580590216,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536336,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580536840,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580960,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580581464,
      "name": "tracing_start_sched_switch.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void tracing_start_sched_switch(int ops)
```

```json
{
  "name": "tracing_start_sched_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_start_sched_switch",
      "external": false,
      "loc": "kernel/trace/trace_sched_switch.c:90",
      "file": "kernel/trace/trace_sched_switch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_sched_switch.c:tracing_start_tgid_record",
        "kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637696,
      "name": "tracing_start_sched_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071580638200,
      "name": "tracing_start_sched_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tracing_start_sched_switch(int ops)
```
</details>
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
