# Function: <code>mem_cgroup_mark_under_oom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580939539,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1625",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581086353,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1490",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161355,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1461",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581208983,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1453",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339351,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1467",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581486776,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1424",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565200,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1605",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565200,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676528,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676528,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748928,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748928,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968784,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1688",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968784,
      "name": "mem_cgroup_mark_under_oom",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017856,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1877",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017856,
      "name": "mem_cgroup_mark_under_oom",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044512,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1700",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044512,
      "name": "mem_cgroup_mark_under_oom",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351376,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1752",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351376,
      "name": "mem_cgroup_mark_under_oom",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847312,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1769",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847312,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393104,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1829",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393104,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612384,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1863",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612384,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583807280,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1935",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807280,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493202184,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493202184,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226833260,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226833260,
      "name": "mem_cgroup_mark_under_oom",
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286707456,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286707456,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272980608,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272980608,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717664,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717664,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656544,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656544,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708976,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708976,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_mark_under_oom",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776480,
      "name": "mem_cgroup_mark_under_oom",
      "external": false,
      "loc": "mm/memcontrol.c:1822",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776480,
      "name": "mem_cgroup_mark_under_oom",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void mem_cgroup_mark_under_oom(struct mem_cgroup * memcg)
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
