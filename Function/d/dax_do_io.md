# Function: <code>dax_do_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t dax_do_io(struct kiocb * iocb, struct inode * inode, struct iov_iter * iter, loff_t pos, get_block_t * get_block, dio_iodone_t * end_io, int flags)
```

```json
{
  "name": "dax_do_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328416,
      "name": "dax_do_io",
      "external": true,
      "loc": "fs/dax.c:209",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328416,
      "name": "dax_do_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t dax_do_io(struct kiocb * iocb, struct inode * inode, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, int flags)
```

```json
{
  "name": "dax_do_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581494096,
      "name": "dax_do_io",
      "external": true,
      "loc": "fs/dax.c:258",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494096,
      "name": "dax_do_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1550
    }
  ]
}
```
</details>
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>loff_t pos</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, iter, pos, get_block, end_io, flags</code> ➡️ <code>iocb, inode, iter, get_block, end_io, flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
ssize_t dax_do_io(struct kiocb * iocb, struct inode * inode, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, int flags)
```
</details>
</li>
</ul>
