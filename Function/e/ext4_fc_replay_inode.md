# Function: <code>ext4_fc_replay_inode</code>

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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl * tl)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388224,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1458",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388224,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410560,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1455",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410560,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755056,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1431",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755056,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315888,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1511",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315888,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl_mem * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584963520,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1517",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963520,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl_mem * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585191808,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1517",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585191808,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl_mem * tl, u8 * val)
```

```json
{
  "name": "ext4_fc_replay_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585424704,
      "name": "ext4_fc_replay_inode",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1517",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424704,
      "name": "ext4_fc_replay_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int ext4_fc_replay_inode(struct super_block * sb, struct ext4_fc_tl * tl)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * val</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>struct ext4_fc_tl * tl</code> ➡️ <code>struct ext4_fc_tl_mem * tl</code>
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
