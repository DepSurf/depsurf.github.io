# Function: <code>virtqueue_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583823937,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:129",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584154309,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:260",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584334885,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:260",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584415909,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:260",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584823478,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:260",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585054725,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:259",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int virtqueue_add(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585161968,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1689",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585161968,
      "name": "virtqueue_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2799
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585374565,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1694",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585514437,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586233845,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586352233,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586235273,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1695",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586744153,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1793",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588019641,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1797",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589395577,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2083",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589694393,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2120",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590027337,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:2197",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498172772,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230932520,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291402656,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275948468,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585276517,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585228981,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585464837,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtqueue_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585573013,
      "name": "virtqueue_add",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1693",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int virtqueue_add(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int virtqueue_add(struct virtqueue * _vq, struct scatterlist * * sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void * data, void * ctx, gfp_t gfp)
```
</details>
</li>
</ul>
