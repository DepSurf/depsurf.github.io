# Function: <code>folio_init_buffers</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
sector_t folio_init_buffers(struct folio * folio, struct block_device * bdev, sector_t block, int size)
```

```json
{
  "name": "folio_init_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_init_buffers",
      "external": false,
      "loc": "fs/buffer.c:1008",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__getblk_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123360,
      "name": "folio_init_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071596574660,
      "name": "folio_init_buffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
sector_t folio_init_buffers(struct folio * folio, struct block_device * bdev, unsigned int size)
```

```json
{
  "name": "folio_init_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_init_buffers",
      "external": false,
      "loc": "fs/buffer.c:996",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__getblk_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340016,
      "name": "folio_init_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071597479331,
      "name": "folio_init_buffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
sector_t folio_init_buffers(struct folio * folio, struct block_device * bdev, sector_t block, int size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sector_t block</code>
</li>
<li>
<b>Param reordered. </b>
<code>folio, bdev, block, size</code> ➡️ <code>folio, bdev, size</code>
</li>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
</li>
</ul>
