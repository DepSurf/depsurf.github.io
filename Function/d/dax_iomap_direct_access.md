# Function: <code>dax_iomap_direct_access</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int dax_iomap_direct_access(const struct iomap * iomap, loff_t pos, size_t size, void * * kaddr, pfn_t * pfnp)
```

```json
{
  "name": "dax_iomap_direct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584053968,
      "name": "dax_iomap_direct_access",
      "external": false,
      "loc": "fs/dax.c:1053",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_file_unshare",
        "fs/dax.c:dax_file_unshare",
        "fs/dax.c:dax_iomap_copy_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053968,
      "name": "dax_iomap_direct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dax_iomap_direct_access(const struct iomap * iomap, loff_t pos, size_t size, void * * kaddr, pfn_t * pfnp)
```

```json
{
  "name": "dax_iomap_direct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278816,
      "name": "dax_iomap_direct_access",
      "external": false,
      "loc": "fs/dax.c:1080",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278816,
      "name": "dax_iomap_direct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dax_iomap_direct_access(const struct iomap * iomap, loff_t pos, size_t size, void * * kaddr, pfn_t * pfnp)
```

```json
{
  "name": "dax_iomap_direct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584495616,
      "name": "dax_iomap_direct_access",
      "external": false,
      "loc": "fs/dax.c:1066",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495616,
      "name": "dax_iomap_direct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int dax_iomap_direct_access(const struct iomap * iomap, loff_t pos, size_t size, void * * kaddr, pfn_t * pfnp)
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
