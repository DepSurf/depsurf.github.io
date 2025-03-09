# Function: <code>memcpy_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022592,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:372",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_to_iter",
        "lib/iov_iter.c:copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022592,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583320785,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:345",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_to_iter"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433488,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:437",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_to_iter",
        "lib/iov_iter.c:copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433488,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452224,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452224,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632320,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632320,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848816,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848816,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932752,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:463",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932752,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110944,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110944,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233744,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233744,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643200,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:469",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643200,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764720,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:476",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764720,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583423310,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:325",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584812917,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:325",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
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
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583772686,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:311",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584903396,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:311",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585237791,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:311",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter"
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
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584333088,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:382",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061548,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:382",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_pipe_to_iter"
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
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127008,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583585530,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584981936,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587045188,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_pipe_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590457502,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:397",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127008,
      "name": "memcpy_to_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127328,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583802714,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585210605,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590777774,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127328,
      "name": "memcpy_to_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579153232,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584008922,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585443469,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591120446,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "include/linux/highmem.h:421",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153232,
      "name": "memcpy_to_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496109680,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496109680,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229434920,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229434920,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290358640,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290358640,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174342,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174342,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202480,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202480,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137696,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137696,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186240,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186240,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```

```json
{
  "name": "memcpy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290512,
      "name": "memcpy_to_page",
      "external": false,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290512,
      "name": "memcpy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, char * from, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void memcpy_to_page(struct page * page, size_t offset, const char * from, size_t len)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
