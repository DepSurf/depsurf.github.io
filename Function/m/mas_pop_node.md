# Function: <code>mas_pop_node</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mas_pop_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595853131,
      "name": "mas_pop_node",
      "external": false,
      "loc": "lib/maple_tree.c:1127",
      "file": "lib/maple_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mtree_alloc_range",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct maple_node * mas_pop_node(struct ma_state * mas)
```

```json
{
  "name": "mas_pop_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596316368,
      "name": "mas_pop_node",
      "external": false,
      "loc": "lib/maple_tree.c:1180",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596316368,
      "name": "mas_pop_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
struct maple_node * mas_pop_node(struct ma_state * mas)
```

```json
{
  "name": "mas_pop_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597201104,
      "name": "mas_pop_node",
      "external": false,
      "loc": "lib/maple_tree.c:1139",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_split_final_node",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance",
        "lib/maple_tree.c:mas_destroy_rebalance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597201104,
      "name": "mas_pop_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct maple_node * mas_pop_node(struct ma_state * mas)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
