# Function: <code>workingset_age_nonresident</code>

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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493728,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:226",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493728,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535280,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:227",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_pages_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535280,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557392,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:227",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_pages_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557392,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821472,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:229",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_pages_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821472,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212432,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:229",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_pages_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212432,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582700496,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:325",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_folios_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700496,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914496,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:355",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_folios_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914496,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
```

```json
{
  "name": "workingset_age_nonresident",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583088384,
      "name": "workingset_age_nonresident",
      "external": true,
      "loc": "mm/workingset.c:355",
      "file": "mm/workingset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:move_folios_to_lru",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583088384,
      "name": "workingset_age_nonresident",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void workingset_age_nonresident(struct lruvec * lruvec, long unsigned int nr_pages)
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
