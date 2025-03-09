# Function: <code>inactive_is_low</code>

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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351424,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2204",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351424,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394848,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2211",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394848,
      "name": "inactive_is_low",
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415328,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2401",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415328,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666624,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2539",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666624,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040928,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2647",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040928,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486064,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2802",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486064,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582700544,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2886",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700544,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
```

```json
{
  "name": "inactive_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872896,
      "name": "inactive_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2186",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872896,
      "name": "inactive_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool inactive_is_low(struct lruvec * lruvec, enum lru_list inactive_lru)
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
