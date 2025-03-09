# Function: <code>add_reservation_in_range</code>

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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed, bool count_only)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743424,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:333",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743424,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793536,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:368",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793536,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821904,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:384",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821904,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:386",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110112,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1046
    },
    {
      "addr": 18446744071592211427,
      "name": "add_reservation_in_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:399",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559184,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
    },
    {
      "addr": 18446744071593990259,
      "name": "add_reservation_in_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:545",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070528,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    },
    {
      "addr": 18446744071596040741,
      "name": "add_reservation_in_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:539",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282944,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
    },
    {
      "addr": 18446744071596562977,
      "name": "add_reservation_in_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed)
```

```json
{
  "name": "add_reservation_in_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_reservation_in_range",
      "external": false,
      "loc": "mm/hugetlb.c:572",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:region_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522288,
      "name": "add_reservation_in_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
    },
    {
      "addr": 18446744071597468479,
      "name": "add_reservation_in_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
long int add_reservation_in_range(struct resv_map * resv, long int f, long int t, struct hugetlb_cgroup * h_cg, struct hstate * h, long int * regions_needed, bool count_only)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool count_only</code>
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
