# Function: <code>should_run_aging</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool should_run_aging(struct lruvec * lruvec, long unsigned int max_seq, long unsigned int * min_seq, struct scan_control * sc, bool can_swap, long unsigned int * nr_to_scan)
```

```json
{
  "name": "should_run_aging",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "should_run_aging",
      "external": false,
      "loc": "mm/vmscan.c:4468",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_nr_to_scan",
        "mm/vmscan.c:lru_gen_age_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487232,
      "name": "should_run_aging",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
    },
    {
      "addr": 18446744071596026171,
      "name": "should_run_aging.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_run_aging",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582729843,
      "name": "should_run_aging",
      "external": false,
      "loc": "mm/vmscan.c:5255",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:try_to_shrink_lruvec"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_run_aging",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582899417,
      "name": "should_run_aging",
      "external": false,
      "loc": "mm/vmscan.c:4586",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:try_to_shrink_lruvec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool should_run_aging(struct lruvec * lruvec, long unsigned int max_seq, long unsigned int * min_seq, struct scan_control * sc, bool can_swap, long unsigned int * nr_to_scan)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool should_run_aging(struct lruvec * lruvec, long unsigned int max_seq, long unsigned int * min_seq, struct scan_control * sc, bool can_swap, long unsigned int * nr_to_scan)
```
</details>
</li>
</ul>
