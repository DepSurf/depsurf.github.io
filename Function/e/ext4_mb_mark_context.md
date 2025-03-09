# Function: <code>ext4_mb_mark_context</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_mb_mark_context(handle_t * handle, struct super_block * sb, bool state, ext4_group_t group, ext4_grpblk_t blkoff, ext4_grpblk_t len, int flags, ext4_grpblk_t * ret_changed)
```

```json
{
  "name": "ext4_mb_mark_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_mark_context",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3972",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141648,
      "name": "ext4_mb_mark_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    },
    {
      "addr": 18446744071597507154,
      "name": "ext4_mb_mark_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int ext4_mb_mark_context(handle_t * handle, struct super_block * sb, bool state, ext4_group_t group, ext4_grpblk_t blkoff, ext4_grpblk_t len, int flags, ext4_grpblk_t * ret_changed)
```
</details>
</li>
</ul>
