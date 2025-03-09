# Function: <code>flush_bufs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440576,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1770",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440576,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563376,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1743",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563376,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783152,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1731",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783152,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585925856,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585925856,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586663691,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1730",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586773595,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1730",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586653643,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1727",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587202715,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1727",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588507358,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1728",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr"
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589948846,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1724",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr"
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590258110,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1724",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr"
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590599086,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1692",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498758336,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498758336,
      "name": "flush_bufs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231373152,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231373152,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291911680,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291911680,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276255334,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276255334,
      "name": "flush_bufs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585686832,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686832,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547456,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547456,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585877008,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877008,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```

```json
{
  "name": "flush_bufs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984128,
      "name": "flush_bufs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1732",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984128,
      "name": "flush_bufs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void flush_bufs(struct virtqueue * vq, bool can_sleep)
```
</details>
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
void flush_bufs(struct virtqueue * vq, bool can_sleep)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
