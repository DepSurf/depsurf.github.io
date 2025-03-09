# Function: <code>ext4_data_block_valid_rcu</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582577312,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577312,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582886965,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:152",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_inode_block_valid"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494226152,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494226152,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227655540,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227655540,
      "name": "ext4_data_block_valid_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287922512,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287922512,
      "name": "ext4_data_block_valid_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273680472,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273680472,
      "name": "ext4_data_block_valid_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582546048,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546048,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582483216,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483216,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582536528,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536528,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_data_block_valid_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582617296,
      "name": "ext4_data_block_valid_rcu",
      "external": false,
      "loc": "fs/ext4/block_validity.c:155",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_data_block_valid",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617296,
      "name": "ext4_data_block_valid_rcu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info * sbi, struct ext4_system_blocks * system_blks, ext4_fsblk_t start_blk, unsigned int count)
```
</details>
</li>
</ul>
