# Function: <code>mem_cgroup_get_max</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485936,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1182",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485936,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571712,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1363",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571712,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682800,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1555",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682800,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755200,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755200,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974960,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1531",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974960,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024560,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1712",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024560,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051072,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1535",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051072,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357888,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1587",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357888,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849472,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1604",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849472,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583395872,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1664",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395872,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615216,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1698",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615216,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810096,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1770",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810096,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493208912,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493208912,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226839604,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226839604,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286717824,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286717824,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272986136,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272986136,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723936,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723936,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662736,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662736,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715248,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715248,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_get_max",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782816,
      "name": "mem_cgroup_get_max",
      "external": true,
      "loc": "mm/memcontrol.c:1566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782816,
      "name": "mem_cgroup_get_max",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup * memcg)
```
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
