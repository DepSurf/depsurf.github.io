# Function: <code>arch_invalidate_pmem</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585288201,
      "name": "arch_invalidate_pmem",
      "external": false,
      "loc": "arch/x86/include/asm/pmem.h:116",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300768,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:153",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300768,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322176,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:153",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322176,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579333040,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:171",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333040,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359440,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:306",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359440,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374032,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374032,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378288,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378288,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417904,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:315",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417904,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417936,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:315",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417936,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420960,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:323",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420960,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484544,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:323",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484544,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564304,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:326",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564304,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672336,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:344",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672336,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686240,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:345",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686240,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720768,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:345",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720768,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490343280,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/arm64/mm/flush.c:89",
      "file": "arch/arm64/mm/flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490343280,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282851312,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/powerpc/lib/pmem.c:22",
      "file": "arch/powerpc/lib/pmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282851312,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_invalidate_pmem",
      "external": false,
      "loc": "include/linux/libnvdimm.h:289",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374192,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374192,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304384,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/pmem.c:pmem_do_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304384,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374112,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374112,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void arch_invalidate_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_invalidate_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382592,
      "name": "arch_invalidate_pmem",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:307",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382592,
      "name": "arch_invalidate_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void arch_invalidate_pmem(void * addr, size_t size)
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
