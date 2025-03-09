# Function: <code>ext4_fc_add_dentry_tlv</code>

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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u16 tag, int parent_ino, int ino, int dlen, const unsigned char * dname, u32 * crc)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386944,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:778",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386944,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u16 tag, int parent_ino, int ino, int dlen, const unsigned char * dname, u32 * crc)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409248,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:778",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409248,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u32 * crc, struct ext4_fc_dentry_update * fc_dentry)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752928,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:746",
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
      "addr": 18446744071583752928,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u32 * crc, struct ext4_fc_dentry_update * fc_dentry)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311808,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:825",
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
      "addr": 18446744071584311808,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u32 * crc, struct ext4_fc_dentry_update * fc_dentry)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584959936,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:816",
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
      "addr": 18446744071584959936,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u32 * crc, struct ext4_fc_dentry_update * fc_dentry)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188272,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:816",
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
      "addr": 18446744071585188272,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u32 * crc, struct ext4_fc_dentry_update * fc_dentry)
```

```json
{
  "name": "ext4_fc_add_dentry_tlv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421168,
      "name": "ext4_fc_add_dentry_tlv",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:816",
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
      "addr": 18446744071585421168,
      "name": "ext4_fc_add_dentry_tlv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
bool ext4_fc_add_dentry_tlv(struct super_block * sb, u16 tag, int parent_ino, int ino, int dlen, const unsigned char * dname, u32 * crc)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_fc_dentry_update * fc_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>u16 tag</code>
</li>
<li>
<b>Param removed. </b>
<code>int parent_ino</code>
</li>
<li>
<b>Param removed. </b>
<code>int ino</code>
</li>
<li>
<b>Param removed. </b>
<code>int dlen</code>
</li>
<li>
<b>Param removed. </b>
<code>const unsigned char * dname</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, tag, parent_ino, ino, dlen, dname, crc</code> ➡️ <code>sb, crc, fc_dentry</code>
</li>
</ul>
</details>
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
