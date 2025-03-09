# Function: <code>vchan_dma_desc_free_list</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586213696,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213696,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719728,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719728,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587992160,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587992160,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589357856,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources",
        "drivers/dma/hsu/hsu.c:hsu_dma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357856,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656496,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources",
        "drivers/dma/hsu/hsu.c:hsu_dma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656496,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589966928,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources",
        "drivers/dma/hsu/hsu.c:hsu_dma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_terminate_all",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589966928,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498013112,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_terminate_all",
        "drivers/dma/amba-pl08x.c:pl08x_free_chan_resources",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498013112,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```

```json
{
  "name": "vchan_dma_desc_free_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230791700,
      "name": "vchan_dma_desc_free_list",
      "external": true,
      "loc": "drivers/dma/virt-dma.c:112",
      "file": "drivers/dma/virt-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_terminate_all",
        "drivers/dma/amba-pl08x.c:pl08x_free_chan_resources",
        "drivers/dma/ti/edma.c:edma_free_chan_resources",
        "drivers/dma/ti/edma.c:edma_terminate_all",
        "drivers/dma/ti/omap-dma.c:omap_dma_terminate_all",
        "drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230791700,
      "name": "vchan_dma_desc_free_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
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
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan * vc, struct list_head * head)
```
</details>
</li>
</ul>
