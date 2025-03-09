# Function: <code>reclaim_throttle</code>

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
void reclaim_throttle(pg_data_t * pgdat, enum vmscan_throttle_state reason)
```

```json
{
  "name": "reclaim_throttle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059504,
      "name": "reclaim_throttle",
      "external": true,
      "loc": "mm/vmscan.c:1043",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059504,
      "name": "reclaim_throttle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
void reclaim_throttle(pg_data_t * pgdat, enum vmscan_throttle_state reason)
```

```json
{
  "name": "reclaim_throttle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531776,
      "name": "reclaim_throttle",
      "external": true,
      "loc": "mm/vmscan.c:1141",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531776,
      "name": "reclaim_throttle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
void reclaim_throttle(pg_data_t * pgdat, enum vmscan_throttle_state reason)
```

```json
{
  "name": "reclaim_throttle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735200,
      "name": "reclaim_throttle",
      "external": true,
      "loc": "mm/vmscan.c:1194",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735200,
      "name": "reclaim_throttle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
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
void reclaim_throttle(pg_data_t * pgdat, enum vmscan_throttle_state reason)
```

```json
{
  "name": "reclaim_throttle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902816,
      "name": "reclaim_throttle",
      "external": true,
      "loc": "mm/vmscan.c:493",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902816,
      "name": "reclaim_throttle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
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
void reclaim_throttle(pg_data_t * pgdat, enum vmscan_throttle_state reason)
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
