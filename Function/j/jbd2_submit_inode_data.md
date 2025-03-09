# Function: <code>jbd2_submit_inode_data</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416000,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:210",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416000,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583438000,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:210",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438000,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583787920,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:210",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787920,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584352144,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:212",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584352144,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(journal_t * journal, struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585001600,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:210",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001600,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(journal_t * journal, struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585229632,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:181",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229632,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_submit_inode_data(journal_t * journal, struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_submit_inode_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585462624,
      "name": "jbd2_submit_inode_data",
      "external": true,
      "loc": "fs/jbd2/commit.c:181",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462624,
      "name": "jbd2_submit_inode_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int jbd2_submit_inode_data(struct jbd2_inode * jinode)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>journal_t * journal</code>
</li>
<li>
<b>Param reordered. </b>
<code>jinode</code> ➡️ <code>journal, jinode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
