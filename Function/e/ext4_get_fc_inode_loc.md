# Function: <code>ext4_get_fc_inode_loc</code>

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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091696,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4468",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091696,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116656,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4467",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116656,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457440,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4388",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457440,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980368,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4609",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980368,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608928,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4704",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608928,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835408,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4489",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835408,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_get_fc_inode_loc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068272,
      "name": "ext4_get_fc_inode_loc",
      "external": true,
      "loc": "fs/ext4/inode.c:4508",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068272,
      "name": "ext4_get_fc_inode_loc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int ext4_get_fc_inode_loc(struct super_block * sb, long unsigned int ino, struct ext4_iloc * iloc)
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
