# Function: <code>update_parent_subparts_cpumask</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580246160,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1084",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246160,
      "name": "update_parent_subparts_cpumask.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580294256,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1045",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294256,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580342608,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342608,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420944,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1121",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420944,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1086
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408352,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1144",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408352,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1086
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408368,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1144",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408368,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571088,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1172",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571088,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1327
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772816,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1210",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772816,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1339
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
int update_parent_subparts_cpumask(struct cpuset * cs, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052928,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1310",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052928,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2704
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
int update_parent_subparts_cpumask(struct cpuset * cs, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1318",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143536,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2858
    },
    {
      "addr": 18446744071596518633,
      "name": "update_parent_subparts_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491606416,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491606416,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225564344,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225564344,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284590400,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284590400,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272008582,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272008582,
      "name": "update_parent_subparts_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311408,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311408,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580258736,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258736,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302656,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302656,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_parent_subparts_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580357120,
      "name": "update_parent_subparts_cpumask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1119",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357120,
      "name": "update_parent_subparts_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
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
<code>struct cpuset * cs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpuset * cpuset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cs, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int update_parent_subparts_cpumask(struct cpuset * cpuset, int cmd, struct cpumask * newmask, struct tmpmasks * tmp)
```
</details>
</li>
</ul>
