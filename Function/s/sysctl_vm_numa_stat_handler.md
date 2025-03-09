# Function: <code>sysctl_vm_numa_stat_handler</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898400,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898400,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037652,
      "name": "sysctl_vm_numa_stat_handler.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581034304,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115236,
      "name": "sysctl_vm_numa_stat_handler.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581111872,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179876,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581176576,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237988,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581234704,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426798,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581423600,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325465,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581466832,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267513,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581487584,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592192774,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581743632,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593968695,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582125600,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600464,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600464,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808080,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808080,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982640,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:77",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982640,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492628320,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492628320,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285945184,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285945184,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206836,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581203552,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153588,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581150304,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198036,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581194752,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
```

```json
{
  "name": "sysctl_vm_numa_stat_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_vm_numa_stat_handler",
      "external": true,
      "loc": "mm/vmstat.c:78",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261316,
      "name": "sysctl_vm_numa_stat_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581258032,
      "name": "sysctl_vm_numa_stat_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
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
int sysctl_vm_numa_stat_handler(struct ctl_table * table, int write, void * buffer, size_t * length, loff_t * ppos)
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
