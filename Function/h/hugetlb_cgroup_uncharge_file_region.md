# Function: <code>hugetlb_cgroup_uncharge_file_region</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990048,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:394",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990048,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040112,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:392",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040112,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066224,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:392",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066224,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582376080,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:392",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582376080,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582876832,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:437",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876832,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424896,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:439",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424896,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583645296,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:435",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645296,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages, bool region_del)
```

```json
{
  "name": "hugetlb_cgroup_uncharge_file_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840080,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "external": true,
      "loc": "mm/hugetlb_cgroup.c:426",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840080,
      "name": "hugetlb_cgroup_uncharge_file_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void hugetlb_cgroup_uncharge_file_region(struct resv_map * resv, struct file_region * rg, long unsigned int nr_pages)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool region_del</code>
</li>
</ul>
</details>
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
