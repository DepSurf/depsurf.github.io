# Function: <code>guarantee_online_mems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006192,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cpuset.c:354",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_mems_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006192,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038688,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cpuset.c:365",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_mems_allowed",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038688,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071696,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cpuset.c:365",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_mems_allowed",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071696,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580077392,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:368",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077392,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130304,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:379",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130304,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189664,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:379",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189664,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238000,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:436",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238000,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288512,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:398",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288512,
      "name": "guarantee_online_mems",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336848,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336848,
      "name": "guarantee_online_mems",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580410416,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:414",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580397728,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:414",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580419735,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:414",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580583047,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:442",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580784110,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:460",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581067758,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:543",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581158110,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:543",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581263614,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:573",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491598856,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491598856,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225558544,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225558544,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284585008,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284585008,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272003860,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272003860,
      "name": "guarantee_online_mems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305648,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305648,
      "name": "guarantee_online_mems",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252976,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252976,
      "name": "guarantee_online_mems",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296896,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296896,
      "name": "guarantee_online_mems",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```

```json
{
  "name": "guarantee_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351536,
      "name": "guarantee_online_mems",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:410",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351536,
      "name": "guarantee_online_mems",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void guarantee_online_mems(struct cpuset * cs, nodemask_t * pmask)
```
</details>
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
