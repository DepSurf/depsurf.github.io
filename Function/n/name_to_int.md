# Function: <code>name_to_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "name_to_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581457664,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462551,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471807,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common"
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
  "name": "name_to_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581641936,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646947,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656307,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common"
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
  "name": "name_to_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581730208,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735243,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744851,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:115",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "name_to_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581784322,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:107",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789697,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:107",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798963,
      "name": "name_to_int",
      "external": false,
      "loc": "fs/proc/internal.h:107",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956336,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:3",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956336,
      "name": "name_to_int",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141552,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:3",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141552,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236176,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236176,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400576,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400576,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499536,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499536,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800864,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800864,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874496,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874496,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902832,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902832,
      "name": "name_to_int",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237024,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237024,
      "name": "name_to_int",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735920,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735920,
      "name": "name_to_int",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584349232,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349232,
      "name": "name_to_int",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584579504,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584579504,
      "name": "name_to_int",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584810720,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584810720,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494123656,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494123656,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227573252,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227573252,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287796160,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287796160,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273606062,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273606062,
      "name": "name_to_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468272,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468272,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405504,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405504,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458752,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458752,
      "name": "name_to_int",
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
unsigned int name_to_int(const struct qstr * qstr)
```

```json
{
  "name": "name_to_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539104,
      "name": "name_to_int",
      "external": true,
      "loc": "fs/proc/util.c:4",
      "file": "fs/proc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/fd.c:proc_lookupfd_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539104,
      "name": "name_to_int",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int name_to_int(const struct qstr * qstr)
```
</details>
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
