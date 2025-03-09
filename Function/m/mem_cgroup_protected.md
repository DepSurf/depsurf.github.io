# Function: <code>mem_cgroup_protected</code>

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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489872,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:5468",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489872,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575648,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:5786",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575648,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686912,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6078",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686912,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760368,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760368,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980160,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6401",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980160,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493214272,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493214272,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226845240,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226845240,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286726032,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286726032,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272990774,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272990774,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729104,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729104,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667872,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667872,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720416,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720416,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_protected",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788416,
      "name": "mem_cgroup_protected",
      "external": true,
      "loc": "mm/memcontrol.c:6418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788416,
      "name": "mem_cgroup_protected",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup * root, struct mem_cgroup * memcg)
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
