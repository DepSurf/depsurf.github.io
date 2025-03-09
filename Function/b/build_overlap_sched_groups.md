# Function: <code>build_overlap_sched_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563346,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/core.c:6132",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
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
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573602,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/core.c:6098",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
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
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579599132,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/core.c:6142",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
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
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579683368,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:704",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712051,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:706",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579743969,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:698",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579783904,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:898",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808336,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808336,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855856,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855856,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899824,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:925",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899824,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894544,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:986",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894544,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902464,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:982",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902464,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019888,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:996",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019888,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173392,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:1012",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173392,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357296,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:1012",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357296,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:1019",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424880,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1832
    },
    {
      "addr": 18446744071596500675,
      "name": "build_overlap_sched_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:1034",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484480,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1726
    },
    {
      "addr": 18446744071597398285,
      "name": "build_overlap_sched_groups.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491052576,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491052576,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225057664,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225057664,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283929648,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283929648,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271651086,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828208,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828208,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762784,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762784,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816224,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816224,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_overlap_sched_groups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861344,
      "name": "build_overlap_sched_groups",
      "external": false,
      "loc": "kernel/sched/topology.c:927",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861344,
      "name": "build_overlap_sched_groups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int build_overlap_sched_groups(struct sched_domain * sd, int cpu)
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
