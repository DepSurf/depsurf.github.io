# Function: <code>write_merkle_tree_block</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int write_merkle_tree_block(struct inode * inode, const u8 * buf, long unsigned int index, const struct merkle_tree_params * params)
```

```json
{
  "name": "write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "write_merkle_tree_block",
      "external": false,
      "loc": "fs/verity/enable.c:49",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330928,
      "name": "write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071596582912,
      "name": "write_merkle_tree_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int write_merkle_tree_block(struct inode * inode, const u8 * buf, long unsigned int index, const struct merkle_tree_params * params)
```

```json
{
  "name": "write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "write_merkle_tree_block",
      "external": false,
      "loc": "fs/verity/enable.c:49",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548752,
      "name": "write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071597487278,
      "name": "write_merkle_tree_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int write_merkle_tree_block(struct inode * inode, const u8 * buf, long unsigned int index, const struct merkle_tree_params * params)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
