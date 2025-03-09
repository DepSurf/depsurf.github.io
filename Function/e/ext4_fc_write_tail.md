# Function: <code>ext4_fc_write_tail</code>

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
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388992,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:719",
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
      "addr": 18446744071583388992,
      "name": "ext4_fc_write_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583416005,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:719",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583758069,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:687",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584313714,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:766",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit"
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584960112,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:753",
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
      "addr": 18446744071584960112,
      "name": "ext4_fc_write_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188416,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:753",
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
      "addr": 18446744071585188416,
      "name": "ext4_fc_write_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```

```json
{
  "name": "ext4_fc_write_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421312,
      "name": "ext4_fc_write_tail",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:753",
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
      "addr": 18446744071585421312,
      "name": "ext4_fc_write_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int ext4_fc_write_tail(struct super_block * sb, u32 crc)
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
