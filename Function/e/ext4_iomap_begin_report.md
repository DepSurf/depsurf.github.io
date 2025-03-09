# Function: <code>ext4_iomap_begin_report</code>

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
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012112,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3517",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012112,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583087376,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3555",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583087376,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112400,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3554",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112400,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3477",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452048,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071592258567,
      "name": "ext4_iomap_begin_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3540",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974000,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446744071594039807,
      "name": "ext4_iomap_begin_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3628",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602432,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446744071596072809,
      "name": "ext4_iomap_begin_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3411",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828464,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071596596312,
      "name": "ext4_iomap_begin_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "ext4_iomap_begin_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_iomap_begin_report",
      "external": false,
      "loc": "fs/ext4/inode.c:3430",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061520,
      "name": "ext4_iomap_begin_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071597501877,
      "name": "ext4_iomap_begin_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_iomap_begin_report(struct inode * inode, loff_t offset, loff_t length, unsigned int flags, struct iomap * iomap, struct iomap * srcmap)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
