# Function: <code>mas_wr_store_setup</code>

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
void mas_wr_store_setup(struct ma_wr_state * wr_mas)
```

```json
{
  "name": "mas_wr_store_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595800496,
      "name": "mas_wr_store_setup",
      "external": false,
      "loc": "lib/maple_tree.c:5611",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595800496,
      "name": "mas_wr_store_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void mas_wr_store_setup(struct ma_wr_state * wr_mas)
```

```json
{
  "name": "mas_wr_store_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596332528,
      "name": "mas_wr_store_setup",
      "external": false,
      "loc": "lib/maple_tree.c:5440",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596332528,
      "name": "mas_wr_store_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mas_wr_store_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597195936,
      "name": "mas_wr_store_setup",
      "external": false,
      "loc": "lib/maple_tree.c:5317",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mas_erase",
        "lib/maple_tree.c:mas_preallocate",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597195936,
      "name": "mas_wr_store_setup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void mas_wr_store_setup(struct ma_wr_state * wr_mas)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void mas_wr_store_setup(struct ma_wr_state * wr_mas)
```
</details>
</li>
</ul>
