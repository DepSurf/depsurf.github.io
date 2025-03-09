# Function: <code>sysctl_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581486354,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:417",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
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
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581670866,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:417",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
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
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581759458,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:417",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810224,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:444",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810224,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959776,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:445",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959776,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144352,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:445",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144352,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238976,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:445",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238976,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403472,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403472,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502432,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502432,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804048,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:418",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804048,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877680,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:419",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877680,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906048,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906048,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240304,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240304,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740032,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:439",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740032,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584354064,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:432",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354064,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584368,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:426",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584368,
      "name": "sysctl_perm",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815840,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:428",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815840,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494127088,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494127088,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227577904,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227577904,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287801888,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287801888,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273608986,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273608986,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471168,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471168,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408400,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408400,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461648,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461648,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
```

```json
{
  "name": "sysctl_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542368,
      "name": "sysctl_perm",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:450",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542368,
      "name": "sysctl_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sysctl_perm(struct ctl_table_header * head, struct ctl_table * table, int op)
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
