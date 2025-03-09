# Function: <code>memcg_reparent_list_lrus</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_list_lrus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_reparent_list_lrus",
      "external": true,
      "loc": "mm/list_lru.c:430",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593974108,
      "name": "memcg_reparent_list_lrus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582209520,
      "name": "memcg_reparent_list_lrus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_list_lrus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_reparent_list_lrus",
      "external": true,
      "loc": "mm/list_lru.c:430",
      "file": "mm/list_lru.c",
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
      "addr": 18446744071596031095,
      "name": "memcg_reparent_list_lrus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582696368,
      "name": "memcg_reparent_list_lrus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void memcg_reparent_list_lrus(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_list_lrus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_reparent_list_lrus",
      "external": true,
      "loc": "mm/list_lru.c:430",
      "file": "mm/list_lru.c",
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
      "addr": 18446744071596553070,
      "name": "memcg_reparent_list_lrus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582910288,
      "name": "memcg_reparent_list_lrus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
void memcg_reparent_list_lrus(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```

```json
{
  "name": "memcg_reparent_list_lrus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_reparent_list_lrus",
      "external": true,
      "loc": "mm/list_lru.c:431",
      "file": "mm/list_lru.c",
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
      "addr": 18446744071597456846,
      "name": "memcg_reparent_list_lrus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583084576,
      "name": "memcg_reparent_list_lrus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup * memcg, struct mem_cgroup * parent)
```
</details>
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
