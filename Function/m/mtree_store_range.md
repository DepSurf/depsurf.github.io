# Function: <code>mtree_store_range</code>

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
int mtree_store_range(struct maple_tree * mt, long unsigned int index, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "mtree_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595849024,
      "name": "mtree_store_range",
      "external": true,
      "loc": "lib/maple_tree.c:6194",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595849024,
      "name": "mtree_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int mtree_store_range(struct maple_tree * mt, long unsigned int index, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "mtree_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596369600,
      "name": "mtree_store_range",
      "external": true,
      "loc": "lib/maple_tree.c:6244",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596369600,
      "name": "mtree_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int mtree_store_range(struct maple_tree * mt, long unsigned int index, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "mtree_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597263648,
      "name": "mtree_store_range",
      "external": true,
      "loc": "lib/maple_tree.c:6311",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597263648,
      "name": "mtree_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1446
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
int mtree_store_range(struct maple_tree * mt, long unsigned int index, long unsigned int last, void * entry, gfp_t gfp)
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
