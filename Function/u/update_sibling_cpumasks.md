# Function: <code>update_sibling_cpumasks</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248576,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1412",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248576,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580301744,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1373",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301744,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580350432,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350432,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580423392,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1449",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423392,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410832,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1472",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410832,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410864,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1472",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410864,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573808,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1509",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573808,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580775552,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1547",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775552,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057040,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1697",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057040,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581148160,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1724",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148160,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248288,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2371",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_partition_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248288,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491610288,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491610288,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225566440,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225566440,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284599808,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284599808,
      "name": "update_sibling_cpumasks",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272010660,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272010660,
      "name": "update_sibling_cpumasks",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319232,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319232,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266528,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266528,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580310480,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310480,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "update_sibling_cpumasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365216,
      "name": "update_sibling_cpumasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1447",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365216,
      "name": "update_sibling_cpumasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void update_sibling_cpumasks(struct cpuset * parent, struct cpuset * cs, struct tmpmasks * tmp)
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
