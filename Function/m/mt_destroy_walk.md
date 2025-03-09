# Function: <code>mt_destroy_walk</code>

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
void mt_destroy_walk(struct maple_enode * enode, unsigned char ma_flags, bool free)
```

```json
{
  "name": "mt_destroy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595785248,
      "name": "mt_destroy_walk",
      "external": false,
      "loc": "lib/maple_tree.c:5531",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_destroy",
        "lib/maple_tree.c:mtree_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595785248,
      "name": "mt_destroy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
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
  "name": "mt_destroy_walk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596310272,
      "name": "mt_destroy_walk",
      "external": false,
      "loc": "lib/maple_tree.c:5365",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_destroy",
        "lib/maple_tree.c:mtree_destroy",
        "lib/maple_tree.c:mas_wmb_replace",
        "lib/maple_tree.c:mas_wmb_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596310272,
      "name": "mt_destroy_walk.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
  "name": "mt_destroy_walk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597198944,
      "name": "mt_destroy_walk",
      "external": false,
      "loc": "lib/maple_tree.c:5242",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/maple_tree.c:mtree_destroy",
        "lib/maple_tree.c:mtree_destroy",
        "lib/maple_tree.c:mas_topiary_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597198944,
      "name": "mt_destroy_walk.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
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
void mt_destroy_walk(struct maple_enode * enode, unsigned char ma_flags, bool free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void mt_destroy_walk(struct maple_enode * enode, unsigned char ma_flags, bool free)
```
</details>
</li>
</ul>
