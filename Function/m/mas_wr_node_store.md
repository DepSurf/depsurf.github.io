# Function: <code>mas_wr_node_store</code>

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
bool mas_wr_node_store(struct ma_wr_state * wr_mas)
```

```json
{
  "name": "mas_wr_node_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mas_wr_node_store",
      "external": false,
      "loc": "lib/maple_tree.c:4059",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_modify",
        "lib/maple_tree.c:mas_wr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595816384,
      "name": "mas_wr_node_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2058
    },
    {
      "addr": 18446744071596373216,
      "name": "mas_wr_node_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
bool mas_wr_node_store(struct ma_wr_state * wr_mas, unsigned char new_end)
```

```json
{
  "name": "mas_wr_node_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mas_wr_node_store",
      "external": false,
      "loc": "lib/maple_tree.c:4078",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596341392,
      "name": "mas_wr_node_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1771
    },
    {
      "addr": 18446744071596902697,
      "name": "mas_wr_node_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool mas_wr_node_store(struct ma_wr_state * wr_mas, unsigned char new_end)
```

```json
{
  "name": "mas_wr_node_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597218256,
      "name": "mas_wr_node_store",
      "external": false,
      "loc": "lib/maple_tree.c:3883",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mas_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597218256,
      "name": "mas_wr_node_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1855
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
bool mas_wr_node_store(struct ma_wr_state * wr_mas)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char new_end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
