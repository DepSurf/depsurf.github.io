# Function: <code>memcg_reparent_objcgs</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004560,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:321",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004560,
      "name": "memcg_reparent_objcgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582033587,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:324",
      "file": "mm/memcontrol.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582339976,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:328",
      "file": "mm/memcontrol.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582817176,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:327",
      "file": "mm/memcontrol.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362288,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:320",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362288,
      "name": "memcg_reparent_objcgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582240,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:324",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582240,
      "name": "memcg_reparent_objcgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_objcgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583776016,
      "name": "memcg_reparent_objcgs",
      "external": false,
      "loc": "mm/memcontrol.c:328",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776016,
      "name": "memcg_reparent_objcgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void memcg_reparent_objcgs(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
