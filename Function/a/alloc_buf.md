# Function: <code>alloc_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584181856,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:420",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:fill_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181856,
      "name": "alloc_buf.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584520976,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:426",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520976,
      "name": "alloc_buf.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703392,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:425",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703392,
      "name": "alloc_buf.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584784768,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:425",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784768,
      "name": "alloc_buf.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585204976,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:425",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204976,
      "name": "alloc_buf.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441408,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:425",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441408,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564784,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:425",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564784,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789296,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789296,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932032,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932032,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663056,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663056,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586772976,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772976,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653056,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653056,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587202128,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202128,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588506992,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:413",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506992,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589948464,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:405",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589948464,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590257728,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:406",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590257728,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590598704,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:403",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590598704,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498758984,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498758984,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231379924,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231379924,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291921888,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291921888,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276255716,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276255716,
      "name": "alloc_buf.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693008,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693008,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585552608,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552608,
      "name": "alloc_buf.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585882256,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585882256,
      "name": "alloc_buf.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```

```json
{
  "name": "alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585990192,
      "name": "alloc_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:412",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990192,
      "name": "alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct port_buffer * alloc_buf(struct virtio_device * vdev, size_t buf_size, int pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
