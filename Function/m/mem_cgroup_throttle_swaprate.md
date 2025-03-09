# Function: <code>mem_cgroup_throttle_swaprate</code>

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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346384,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3727",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346384,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456704,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3732",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456704,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520864,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520864,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492944456,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492944456,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226730476,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226730476,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286358048,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286358048,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272861692,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272861692,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489600,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489600,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431856,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431856,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480912,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480912,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_throttle_swaprate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545680,
      "name": "mem_cgroup_throttle_swaprate",
      "external": true,
      "loc": "mm/swapfile.c:3740",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545680,
      "name": "mem_cgroup_throttle_swaprate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_throttle_swaprate(struct mem_cgroup * memcg, int node, gfp_t gfp_mask)
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
