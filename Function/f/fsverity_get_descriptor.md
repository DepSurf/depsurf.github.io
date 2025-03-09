# Function: <code>fsverity_get_descriptor</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret, size_t * desc_size_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:266",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591286492,
      "name": "fsverity_get_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071582712464,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret, size_t * desc_size_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:266",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592243244,
      "name": "fsverity_get_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071583039104,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:265",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594022292,
      "name": "fsverity_get_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071583513728,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111952,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:265",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111952,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338032,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:325",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:__fsverity_file_open",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338032,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret)
```

```json
{
  "name": "fsverity_get_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556240,
      "name": "fsverity_get_descriptor",
      "external": true,
      "loc": "fs/verity/open.c:325",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:__fsverity_file_open",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556240,
      "name": "fsverity_get_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int fsverity_get_descriptor(struct inode * inode, struct fsverity_descriptor * * desc_ret, size_t * desc_size_ret)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t * desc_size_ret</code>
</li>
</ul>
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
