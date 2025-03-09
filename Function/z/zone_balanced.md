# Function: <code>zone_balanced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool zone_balanced(struct zone * zone, int order, long unsigned int balance_gap, int classzone_idx)
```

```json
{
  "name": "zone_balanced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580552112,
      "name": "zone_balanced",
      "external": false,
      "loc": "mm/vmscan.c:2959",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:pgdat_balanced",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552112,
      "name": "zone_balanced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool zone_balanced(struct zone * zone, int order, int classzone_idx)
```

```json
{
  "name": "zone_balanced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580643280,
      "name": "zone_balanced",
      "external": false,
      "loc": "mm/vmscan.c:3079",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:prepare_kswapd_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643280,
      "name": "zone_balanced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool zone_balanced(struct zone * zone, int order, int classzone_idx)
```

```json
{
  "name": "zone_balanced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710352,
      "name": "zone_balanced",
      "external": false,
      "loc": "mm/vmscan.c:3090",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:prepare_kswapd_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710352,
      "name": "zone_balanced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int balance_gap</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, balance_gap, classzone_idx</code> ➡️ <code>zone, order, classzone_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool zone_balanced(struct zone * zone, int order, int classzone_idx)
```
</details>
</li>
</ul>
