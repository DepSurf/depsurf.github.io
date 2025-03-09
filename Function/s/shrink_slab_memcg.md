# Function: <code>shrink_slab_memcg</code>

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
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581044558,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:583",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581110249,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:595",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581166985,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362544,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:550",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362544,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406144,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:543",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406144,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427136,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:744",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427136,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679072,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:790",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679072,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055808,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:802",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055808,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528416,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:879",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528416,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582731216,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:932",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731216,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927056,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/shrinker.c:467",
      "file": "mm/shrinker.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shrinker.c:shrink_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927056,
      "name": "shrink_slab_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492549044,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226409832,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285845296,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272592406,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581135833,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581082777,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581127033,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581189521,
      "name": "shrink_slab_memcg",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
