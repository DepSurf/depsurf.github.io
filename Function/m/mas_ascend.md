# Function: <code>mas_ascend</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int mas_ascend(struct ma_state * mas)
```

```json
{
  "name": "mas_ascend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595792128,
      "name": "mas_ascend",
      "external": false,
      "loc": "lib/maple_tree.c:1049",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_alloc_rrange",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_next_node",
        "lib/maple_tree.c:mas_prev_node",
        "lib/maple_tree.c:mas_push_data",
        "lib/maple_tree.c:mast_fill_bnode",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595792128,
      "name": "mas_ascend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int mas_ascend(struct ma_state * mas)
```

```json
{
  "name": "mas_ascend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596318896,
      "name": "mas_ascend",
      "external": false,
      "loc": "lib/maple_tree.c:1094",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_next_node",
        "lib/maple_tree.c:mas_prev_node",
        "lib/maple_tree.c:mas_push_data",
        "lib/maple_tree.c:mast_fill_bnode",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596318896,
      "name": "mas_ascend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int mas_ascend(struct ma_state * mas)
```

```json
{
  "name": "mas_ascend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597203232,
      "name": "mas_ascend",
      "external": false,
      "loc": "lib/maple_tree.c:1051",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area_rev",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_empty_area",
        "lib/maple_tree.c:mas_next_node",
        "lib/maple_tree.c:mas_prev_node",
        "lib/maple_tree.c:mas_push_data",
        "lib/maple_tree.c:mast_fill_bnode",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597203232,
      "name": "mas_ascend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int mas_ascend(struct ma_state * mas)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
