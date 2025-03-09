# Function: <code>mem_cgroup_oom_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580939867,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3359",
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
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581086676,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3365",
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
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161653,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3338",
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
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209231,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3357",
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
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339599,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3384",
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
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487076,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3315",
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565296,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3590",
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
      "addr": 18446744071581565296,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676624,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3915",
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
      "addr": 18446744071581676624,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749024,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446744071581749024,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968880,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:3988",
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
      "addr": 18446744071581968880,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017952,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4254",
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
      "addr": 18446744071582017952,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044608,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4037",
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
      "addr": 18446744071582044608,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351472,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4204",
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
      "addr": 18446744071582351472,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847424,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4155",
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
      "addr": 18446744071582847424,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393232,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4265",
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
      "addr": 18446744071583393232,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612512,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4289",
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
      "addr": 18446744071583612512,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583807408,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4486",
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
      "addr": 18446744071583807408,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493202384,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446603336493202384,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226833388,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 3226833388,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286707696,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 13835058055286707696,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272980766,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446743936272980766,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717760,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446744071581717760,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656640,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446744071581656640,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709072,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446744071581709072,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776576,
      "name": "mem_cgroup_oom_notify",
      "external": false,
      "loc": "mm/memcontrol.c:4108",
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
      "addr": 18446744071581776576,
      "name": "mem_cgroup_oom_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void mem_cgroup_oom_notify(struct mem_cgroup * memcg)
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
