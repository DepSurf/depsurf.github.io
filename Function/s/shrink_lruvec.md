# Function: <code>shrink_lruvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void shrink_lruvec(struct lruvec * lruvec, int swappiness, struct scan_control * sc, long unsigned int * lru_pages)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566128,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2182",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:mem_cgroup_shrink_node_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566128,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
    }
  ]
}
```
</details>
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369824,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2426",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369824,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413472,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2434",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413472,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434704,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2632",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434704,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687776,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2786",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687776,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061616,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:2892",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061616,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534160,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:5912",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534160,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737568,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:6271",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737568,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
```

```json
{
  "name": "shrink_lruvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905184,
      "name": "shrink_lruvec",
      "external": false,
      "loc": "mm/vmscan.c:5635",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905184,
      "name": "shrink_lruvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void shrink_lruvec(struct lruvec * lruvec, int swappiness, struct scan_control * sc, long unsigned int * lru_pages)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void shrink_lruvec(struct lruvec * lruvec, struct scan_control * sc)
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
