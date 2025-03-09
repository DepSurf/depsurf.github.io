# Function: <code>__memcpy_flushcache</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446992,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:156",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446992,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904896,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904896,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130880,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130880,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135168,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:138",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135168,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286528,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:117",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286528,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170224,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:117",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170224,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623920,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:117",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623920,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783072,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:115",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783072,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595949328,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:75",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595949328,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596466784,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:80",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596466784,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597361776,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:80",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597361776,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733136,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733136,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458816,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/pmem.c:write_pmem",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458816,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176512,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176512,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "__memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226960,
      "name": "__memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:137",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226960,
      "name": "__memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __memcpy_flushcache(void * _dst, const void * _src, size_t size)
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
