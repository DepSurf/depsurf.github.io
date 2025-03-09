# Function: <code>gnttab_alloc_grant_reference_seq</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t * first)
```

```json
{
  "name": "gnttab_alloc_grant_reference_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055056,
      "name": "gnttab_alloc_grant_reference_seq",
      "external": true,
      "loc": "drivers/xen/grant-table.c:645",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055056,
      "name": "gnttab_alloc_grant_reference_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t * first)
```

```json
{
  "name": "gnttab_alloc_grant_reference_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433936,
      "name": "gnttab_alloc_grant_reference_seq",
      "external": true,
      "loc": "drivers/xen/grant-table.c:645",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433936,
      "name": "gnttab_alloc_grant_reference_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t * first)
```

```json
{
  "name": "gnttab_alloc_grant_reference_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733072,
      "name": "gnttab_alloc_grant_reference_seq",
      "external": true,
      "loc": "drivers/xen/grant-table.c:663",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733072,
      "name": "gnttab_alloc_grant_reference_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t * first)
```

```json
{
  "name": "gnttab_alloc_grant_reference_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590071040,
      "name": "gnttab_alloc_grant_reference_seq",
      "external": true,
      "loc": "drivers/xen/grant-table.c:661",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071040,
      "name": "gnttab_alloc_grant_reference_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int gnttab_alloc_grant_reference_seq(unsigned int count, grant_ref_t * first)
```
</details>
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
