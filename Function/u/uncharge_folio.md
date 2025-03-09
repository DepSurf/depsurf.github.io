# Function: <code>uncharge_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void uncharge_folio(struct folio * folio, struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845936,
      "name": "uncharge_folio",
      "external": false,
      "loc": "mm/memcontrol.c:6852",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845936,
      "name": "uncharge_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
void uncharge_folio(struct folio * folio, struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390448,
      "name": "uncharge_folio",
      "external": false,
      "loc": "mm/memcontrol.c:7041",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390448,
      "name": "uncharge_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
void uncharge_folio(struct folio * folio, struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583611152,
      "name": "uncharge_folio",
      "external": false,
      "loc": "mm/memcontrol.c:7109",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611152,
      "name": "uncharge_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
void uncharge_folio(struct folio * folio, struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583805856,
      "name": "uncharge_folio",
      "external": false,
      "loc": "mm/memcontrol.c:7436",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805856,
      "name": "uncharge_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void uncharge_folio(struct folio * folio, struct uncharge_gather * ug)
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
