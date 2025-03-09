# Function: <code>ext4_update_backup_sb</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_update_backup_sb(struct super_block * sb, handle_t * handle, ext4_group_t grp, ext4_update_sb_callback * func, const void * arg)
```

```json
{
  "name": "ext4_update_backup_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011616,
      "name": "ext4_update_backup_sb",
      "external": false,
      "loc": "fs/ext4/ioctl.c:93",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011616,
      "name": "ext4_update_backup_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int ext4_update_backup_sb(struct super_block * sb, handle_t * handle, ext4_group_t grp, ext4_update_sb_callback * func, const void * arg)
```

```json
{
  "name": "ext4_update_backup_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584642000,
      "name": "ext4_update_backup_sb",
      "external": false,
      "loc": "fs/ext4/ioctl.c:103",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642000,
      "name": "ext4_update_backup_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int ext4_update_backup_sb(struct super_block * sb, handle_t * handle, ext4_group_t grp, ext4_update_sb_callback * func, const void * arg)
```

```json
{
  "name": "ext4_update_backup_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864912,
      "name": "ext4_update_backup_sb",
      "external": false,
      "loc": "fs/ext4/ioctl.c:103",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864912,
      "name": "ext4_update_backup_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int ext4_update_backup_sb(struct super_block * sb, handle_t * handle, ext4_group_t grp, ext4_update_sb_callback * func, const void * arg)
```

```json
{
  "name": "ext4_update_backup_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097808,
      "name": "ext4_update_backup_sb",
      "external": false,
      "loc": "fs/ext4/ioctl.c:103",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097808,
      "name": "ext4_update_backup_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int ext4_update_backup_sb(struct super_block * sb, handle_t * handle, ext4_group_t grp, ext4_update_sb_callback * func, const void * arg)
```
</details>
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
