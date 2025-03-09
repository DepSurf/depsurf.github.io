# Function: <code>copy_mc_to_kernel</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273552,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273552,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585157072,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157072,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585609920,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609920,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766432,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766432,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595931232,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "fs/dax.c:dax_file_unshare",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595931232,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596449600,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_user_large_folio",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:__wp_page_copy_user",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596449600,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```

```json
{
  "name": "copy_mc_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597344960,
      "name": "copy_mc_to_kernel",
      "external": true,
      "loc": "arch/x86/lib/copy_mc.c:62",
      "file": "arch/x86/lib/copy_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_user_large_folio",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:__wp_page_copy_user",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/coredump.c:dump_user_range",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597344960,
      "name": "copy_mc_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long unsigned int copy_mc_to_kernel(void * dst, const void * src, unsigned int len)
```
</details>
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
