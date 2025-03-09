# Function: <code>xen_grant_dma_alloc</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_grant_dma_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_grant_dma_alloc",
      "external": false,
      "loc": "drivers/xen/grant-dma-ops.c:62",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * xen_grant_dma_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "xen_grant_dma_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_grant_dma_alloc",
      "external": false,
      "loc": "drivers/xen/grant-dma-ops.c:78",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589547680,
      "name": "xen_grant_dma_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071596231291,
      "name": "xen_grant_dma_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * xen_grant_dma_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "xen_grant_dma_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_grant_dma_alloc",
      "external": false,
      "loc": "drivers/xen/grant-dma-ops.c:78",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589849264,
      "name": "xen_grant_dma_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071596759199,
      "name": "xen_grant_dma_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void * xen_grant_dma_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "xen_grant_dma_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_grant_dma_alloc",
      "external": false,
      "loc": "drivers/xen/grant-dma-ops.c:78",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590186528,
      "name": "xen_grant_dma_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071597667650,
      "name": "xen_grant_dma_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void * xen_grant_dma_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
