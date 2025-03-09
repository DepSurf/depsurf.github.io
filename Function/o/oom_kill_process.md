# Function: <code>oom_kill_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control * oc, struct task_struct * p, unsigned int points, long unsigned int totalpages, struct mem_cgroup * memcg, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486608,
      "name": "oom_kill_process",
      "external": true,
      "loc": "mm/oom_kill.c:509",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486608,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
void oom_kill_process(struct oom_control * oc, struct task_struct * p, unsigned int points, long unsigned int totalpages, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580570560,
      "name": "oom_kill_process",
      "external": true,
      "loc": "mm/oom_kill.c:813",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570560,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636464,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:807",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636464,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580668480,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:812",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668480,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753488,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:836",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753488,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:838",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888144,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580892019,
      "name": "oom_kill_process.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:938",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961904,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071580966077,
      "name": "oom_kill_process.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:950",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057728,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581061611,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113488,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581117384,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:953",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297408,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071581301126,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:957",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341456,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    },
    {
      "addr": 18446744071591324921,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:956",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359936,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071591266962,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:957",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607776,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071592190833,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:1014",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967248,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071593966203,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403328,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:1013",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403328,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609344,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:1013",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609344,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780720,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:1009",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780720,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492481280,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492481280,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226355520,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226355520,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285766416,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285766416,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272547164,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272547164,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082336,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581086232,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029520,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581033416,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073536,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581077432,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void oom_kill_process(struct oom_control * oc, const char * message)
```

```json
{
  "name": "oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:951",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135248,
      "name": "oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071581139309,
      "name": "oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>oc, p, points, totalpages, memcg, message</code> ➡️ <code>oc, p, points, totalpages, message</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * p</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int points</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int totalpages</code>
</li>
<li>
<b>Param reordered. </b>
<code>oc, p, points, totalpages, message</code> ➡️ <code>oc, message</code>
</li>
</ul>
</details>
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
