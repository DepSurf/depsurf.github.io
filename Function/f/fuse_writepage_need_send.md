# Function: <code>fuse_writepage_need_send</code>

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
bool fuse_writepage_need_send(struct fuse_conn * fc, struct page * page, struct fuse_args_pages * ap, struct fuse_fill_wb_data * data)
```

```json
{
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528560,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2019",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528560,
      "name": "fuse_writepage_need_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool fuse_writepage_need_send(struct fuse_conn * fc, struct page * page, struct fuse_args_pages * ap, struct fuse_fill_wb_data * data)
```

```json
{
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638096,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2059",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583638096,
      "name": "fuse_writepage_need_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583677299,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2070",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584036213,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2099",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624657,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2118",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585304481,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2153",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585534401,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2130",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "fuse_writepage_need_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585771649,
      "name": "fuse_writepage_need_send",
      "external": false,
      "loc": "fs/fuse/file.c:2150",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill"
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
bool fuse_writepage_need_send(struct fuse_conn * fc, struct page * page, struct fuse_args_pages * ap, struct fuse_fill_wb_data * data)
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
bool fuse_writepage_need_send(struct fuse_conn * fc, struct page * page, struct fuse_args_pages * ap, struct fuse_fill_wb_data * data)
```
</details>
</li>
</ul>
