# Function: <code>ext4_try_to_trim_range</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_try_to_trim_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_try_to_trim_range",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6298",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_discard_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514992,
      "name": "ext4_try_to_trim_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1057
    },
    {
      "addr": 18446744071592263431,
      "name": "ext4_try_to_trim_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_try_to_trim_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584047616,
      "name": "ext4_try_to_trim_range",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6385",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_discard_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047616,
      "name": "ext4_try_to_trim_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_try_to_trim_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679376,
      "name": "ext4_try_to_trim_range",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6354",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_discard_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679376,
      "name": "ext4_try_to_trim_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_try_to_trim_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905088,
      "name": "ext4_try_to_trim_range",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6930",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_discard_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905088,
      "name": "ext4_try_to_trim_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_try_to_trim_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_try_to_trim_range",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6767",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_discard_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585133312,
      "name": "ext4_try_to_trim_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
    },
    {
      "addr": 18446744071597506968,
      "name": "ext4_try_to_trim_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_try_to_trim_range(struct super_block * sb, struct ext4_buddy * e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```
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
