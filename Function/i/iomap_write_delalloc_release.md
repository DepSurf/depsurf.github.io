# Function: <code>iomap_write_delalloc_release</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int iomap_write_delalloc_release(struct inode * inode, loff_t start_byte, loff_t end_byte, int (*)(struct inode *, loff_t, loff_t) punch)
```

```json
{
  "name": "iomap_write_delalloc_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202608,
      "name": "iomap_write_delalloc_release",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:954",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202608,
      "name": "iomap_write_delalloc_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int iomap_write_delalloc_release(struct inode * inode, loff_t start_byte, loff_t end_byte, int (*)(struct inode *, loff_t, loff_t) punch)
```

```json
{
  "name": "iomap_write_delalloc_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432560,
      "name": "iomap_write_delalloc_release",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:974",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432560,
      "name": "iomap_write_delalloc_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
int iomap_write_delalloc_release(struct inode * inode, loff_t start_byte, loff_t end_byte, iomap_punch_t punch)
```

```json
{
  "name": "iomap_write_delalloc_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_delalloc_release",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1140",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653712,
      "name": "iomap_write_delalloc_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
    },
    {
      "addr": 18446744071597488498,
      "name": "iomap_write_delalloc_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int iomap_write_delalloc_release(struct inode * inode, loff_t start_byte, loff_t end_byte, int (*)(struct inode *, loff_t, loff_t) punch)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct inode *, loff_t, loff_t) punch</code> ➡️ <code>iomap_punch_t punch</code>
</li>
</ul>
</details>
</li>
</ul>
