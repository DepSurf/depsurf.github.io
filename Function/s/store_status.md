# Function: <code>store_status</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t store_status(struct kobject * a, struct attribute * b, const char * buf, size_t count)
```

```json
{
  "name": "store_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629152,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1013",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629152,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
ssize_t store_status(struct kobject * a, struct attribute * b, const char * buf, size_t count)
```

```json
{
  "name": "store_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587111744,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:828",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111744,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407925,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1461",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587410208,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:859",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410208,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581491413,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1494",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587590288,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:921",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587590288,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581599258,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1489",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587866608,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:958",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866608,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581669832,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071840,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:957",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071840,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581889231,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1507",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934336,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:964",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934336,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935635,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1624",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588944528,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1066",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944528,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961139,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1606",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588833904,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1068",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588833904,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265998,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1650",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589531328,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1168",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589531328,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582734868,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1581",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591022496,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1201",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591022496,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259412,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1688",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592733760,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1176",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592733760,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583479813,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:2019",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593170880,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1196",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593170880,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583672285,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:2043",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:move_pages_and_store_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593924192,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1220",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593924192,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493099104,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493099104,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286562272,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286562272,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581638568,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693984,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:957",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693984,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581579528,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587470112,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:957",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470112,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581629880,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588027984,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:957",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027984,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int store_status(int * status, int start, int value, int nr)
```

```json
{
  "name": "store_status",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696184,
      "name": "store_status",
      "external": false,
      "loc": "mm/migrate.c:1490",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588143456,
      "name": "store_status",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:957",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143456,
      "name": "store_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
ssize_t store_status(struct kobject * a, struct attribute * b, const char * buf, size_t count)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * status</code>
</li>
<li>
<b>Param added. </b>
<code>int start</code>
</li>
<li>
<b>Param added. </b>
<code>int value</code>
</li>
<li>
<b>Param added. </b>
<code>int nr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * a</code>
</li>
<li>
<b>Param removed. </b>
<code>struct attribute * b</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int store_status(int * status, int start, int value, int nr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int store_status(int * status, int start, int value, int nr)
```
</details>
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
