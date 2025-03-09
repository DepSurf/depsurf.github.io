# Function: <code>memcpy_flushcache</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271552,
      "name": "memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:136",
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
      "addr": 18446744071588271552,
      "name": "memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588827312,
      "name": "memcpy_flushcache",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:136",
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
      "addr": 18446744071588827312,
      "name": "memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void memcpy_flushcache(void * _dst, const void * _src, size_t size)
```

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205408,
      "name": "memcpy_flushcache",
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
      "addr": 18446744071589205408,
      "name": "memcpy_flushcache",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583948493,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:135",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189293,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:135",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589447850,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:135",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584125482,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426500,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589905632,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584250762,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573140,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131616,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584655180,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135776,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358002,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584773120,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287056,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419267,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584803212,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170752,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587301207,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585231715,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624448,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868039,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586070052,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783671,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589217399,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:88",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056997,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:110",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590773175,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:110",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595949959,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:110",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587312249,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:80",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591114576,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:80",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579599345,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:80",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587587595,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:80",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591460000,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:80",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void memcpy_flushcache(void * dst, const void * src, size_t cnt)
```

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503801144,
      "name": "memcpy_flushcache",
      "external": true,
      "loc": "arch/arm64/lib/uaccess_flushcache.c:10",
      "file": "arch/arm64/lib/uaccess_flushcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "arch/arm64/lib/uaccess_flushcache.c:memcpy_page_flushcache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503801144,
      "name": "memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * memcpy_flushcache(void * dest, const void * src, size_t size)
```

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282851424,
      "name": "memcpy_flushcache",
      "external": true,
      "loc": "arch/powerpc/lib/pmem.c:43",
      "file": "arch/powerpc/lib/pmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/lib/pmem.c:memcpy_page_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282851424,
      "name": "memcpy_flushcache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
  "name": "memcpy_flushcache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276684384,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "include/linux/string.h:172",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584219498,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586263620,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733872,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584154714,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090250,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081988,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098635,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:write_pmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459552,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584203258,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586521108,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177248,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "memcpy_flushcache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584307786,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632852,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227703,
      "name": "memcpy_flushcache",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void memcpy_flushcache(void * _dst, const void * _src, size_t size)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void memcpy_flushcache(void * _dst, const void * _src, size_t size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void memcpy_flushcache(void * dst, const void * src, size_t cnt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * memcpy_flushcache(void * dest, const void * src, size_t size)
```
</details>
</li>
</ul>
