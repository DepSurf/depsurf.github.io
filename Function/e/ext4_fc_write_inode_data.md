# Function: <code>ext4_fc_write_inode_data</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386528,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:852",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386528,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408848,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:852",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408848,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752528,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:819",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752528,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311328,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:899",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311328,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584959440,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:889",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584959440,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187776,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:889",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187776,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
```

```json
{
  "name": "ext4_fc_write_inode_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585420672,
      "name": "ext4_fc_write_inode_data",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:889",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420672,
      "name": "ext4_fc_write_inode_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int ext4_fc_write_inode_data(struct inode * inode, u32 * crc)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
