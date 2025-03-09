# Function: <code>xen_dma_sync_for_cpu</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
void xen_dma_sync_for_cpu(struct device * dev, dma_addr_t handle, phys_addr_t paddr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "xen_dma_sync_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490617520,
      "name": "xen_dma_sync_for_cpu",
      "external": true,
      "loc": "arch/arm/xen/mm.c:73",
      "file": "arch/arm/xen/mm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490617520,
      "name": "xen_dma_sync_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void xen_dma_sync_for_cpu(struct device * dev, dma_addr_t handle, phys_addr_t paddr, size_t size, enum dma_data_direction dir)
```
</details>
</li>
</ul>
