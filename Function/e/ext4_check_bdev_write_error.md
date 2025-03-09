# Function: <code>ext4_check_bdev_write_error</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_check_bdev_write_error(struct super_block * sb)
```

```json
{
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582892656,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:198",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892656,
      "name": "ext4_check_bdev_write_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_check_bdev_write_error(struct super_block * sb)
```

```json
{
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964992,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:198",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964992,
      "name": "ext4_check_bdev_write_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582992309,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:198",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
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
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583328540,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:200",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
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
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583837083,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:200",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584460539,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:206",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584689435,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:206",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_bdev_write_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584922285,
      "name": "ext4_check_bdev_write_error",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:207",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ext4_check_bdev_write_error(struct super_block * sb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void ext4_check_bdev_write_error(struct super_block * sb)
```
</details>
</li>
</ul>
