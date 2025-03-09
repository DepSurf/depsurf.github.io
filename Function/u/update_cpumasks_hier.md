# Function: <code>update_cpumasks_hier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580010939,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cpuset.c:869",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
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
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580043450,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cpuset.c:880",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
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
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580081352,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cpuset.c:880",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
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
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580087155,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:883",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580140069,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:895",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199594,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:896",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247280,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1259",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247280,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1220",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300384,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1350
    },
    {
      "addr": 18446744071580309069,
      "name": "update_cpumasks_hier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580349072,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349072,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422032,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1296",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422032,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1348
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409440,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1319",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409440,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1386
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409472,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1319",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409472,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1386
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572416,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1354",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572416,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1390
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774160,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1392",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774160,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp, bool force)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055648,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1545",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055648,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1361
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp, bool force)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1553",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146416,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1717
    },
    {
      "addr": 18446744071596518676,
      "name": "update_cpumasks_hier.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp, int flags)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2181",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246384,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
    },
    {
      "addr": 18446744071597418972,
      "name": "update_cpumasks_hier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491608912,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491608912,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225565160,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225565160,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284598240,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284598240,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272009434,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272009434,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1226
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317872,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317872,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265168,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265168,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309120,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309120,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_cpumasks_hier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580363776,
      "name": "update_cpumasks_hier",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363776,
      "name": "update_cpumasks_hier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void update_cpumasks_hier(struct cpuset * cs, struct tmpmasks * tmp)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force</code>
</li>
</ul>
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
