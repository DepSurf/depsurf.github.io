# Function: <code>drain_obj_stock</code>

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
void drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008256,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3181",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008256,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037136,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3025",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037136,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void drain_obj_stock(struct obj_stock * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344528,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3150",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344528,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
struct obj_cgroup * drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839824,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3141",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839824,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
struct obj_cgroup * drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385312,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3241",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385312,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
struct obj_cgroup * drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605968,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3251",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605968,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
struct obj_cgroup * drain_obj_stock(struct memcg_stock_pcp * stock)
```

```json
{
  "name": "drain_obj_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800704,
      "name": "drain_obj_stock",
      "external": false,
      "loc": "mm/memcontrol.c:3443",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:drain_local_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800704,
      "name": "drain_obj_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
void drain_obj_stock(struct memcg_stock_pcp * stock)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct memcg_stock_pcp * stock</code> ➡️ <code>struct obj_stock * stock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct obj_stock * stock</code> ➡️ <code>struct memcg_stock_pcp * stock</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct obj_cgroup *</code>
</li>
</ul>
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
