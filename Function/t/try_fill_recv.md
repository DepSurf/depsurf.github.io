# Function: <code>try_fill_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```

```json
{
  "name": "try_fill_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585081840,
      "name": "try_fill_recv",
      "external": false,
      "loc": "drivers/net/virtio_net.c:661",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585081840,
      "name": "try_fill_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1550
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
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```

```json
{
  "name": "try_fill_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474176,
      "name": "try_fill_recv",
      "external": false,
      "loc": "drivers/net/virtio_net.c:633",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:refill_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474176,
      "name": "try_fill_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1691
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```

```json
{
  "name": "try_fill_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_fill_recv",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1778",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591765280,
      "name": "try_fill_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071596796351,
      "name": "try_fill_recv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```

```json
{
  "name": "try_fill_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_fill_recv",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1998",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592511824,
      "name": "try_fill_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1098
    },
    {
      "addr": 18446744071597719860,
      "name": "try_fill_recv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool try_fill_recv(struct virtnet_info * vi, struct receive_queue * rq, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
