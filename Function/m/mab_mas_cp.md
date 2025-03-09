# Function: <code>mab_mas_cp</code>

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
void mab_mas_cp(struct maple_big_node * b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state * mas, bool new_max)
```

```json
{
  "name": "mab_mas_cp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mab_mas_cp",
      "external": false,
      "loc": "lib/maple_tree.c:1987",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_reuse_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595780608,
      "name": "mab_mas_cp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1325
    },
    {
      "addr": 18446744071596373149,
      "name": "mab_mas_cp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void mab_mas_cp(struct maple_big_node * b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state * mas, bool new_max)
```

```json
{
  "name": "mab_mas_cp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mab_mas_cp",
      "external": false,
      "loc": "lib/maple_tree.c:2047",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_reuse_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596305216,
      "name": "mab_mas_cp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1399
    },
    {
      "addr": 18446744071596902632,
      "name": "mab_mas_cp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void mab_mas_cp(struct maple_big_node * b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state * mas, bool new_max)
```

```json
{
  "name": "mab_mas_cp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597193696,
      "name": "mab_mas_cp",
      "external": false,
      "loc": "lib/maple_tree.c:1988",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_reuse_node",
        "lib/maple_tree.c:mast_split_data",
        "lib/maple_tree.c:mast_split_data",
        "lib/maple_tree.c:mas_split_final_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597193696,
      "name": "mab_mas_cp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
void mab_mas_cp(struct maple_big_node * b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state * mas, bool new_max)
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
