# Function: <code>force_dma_unencrypted</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579946883,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "kernel/dma/direct.c:27",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995419,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "kernel/dma/direct.c:29",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427328,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:356",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427328,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430496,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430496,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456016,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_coherent_ok",
        "kernel/dma/direct.c:dma_direct_optimal_gfp_mask",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456016,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452608,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:394",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_pgprot",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452608,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455024,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:393",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_pgprot",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455024,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:394",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_pgprot",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592092935,
      "name": "force_dma_unencrypted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579520432,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:17",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593860228,
      "name": "force_dma_unencrypted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579604592,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:17",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595971562,
      "name": "force_dma_unencrypted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579718352,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:17",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596489141,
      "name": "force_dma_unencrypted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579731904,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:18",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:dma_direct_get_required_mask",
        "kernel/dma/swiotlb.c:swiotlb_alloc_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597385763,
      "name": "force_dma_unencrypted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579766848,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "include/linux/dma-direct.h:46",
      "file": "kernel/dma/direct.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "include/linux/dma-direct.h:46",
      "file": "kernel/dma/direct.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284216852,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "arch/powerpc/include/asm/mem_encrypt.h:18",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "force_dma_unencrypted",
      "external": false,
      "loc": "include/linux/dma-direct.h:46",
      "file": "kernel/dma/direct.c",
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426336,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_coherent_ok",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426336,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355440,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355440,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426256,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426256,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool force_dma_unencrypted(struct device * dev)
```

```json
{
  "name": "force_dma_unencrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435440,
      "name": "force_dma_unencrypted",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:354",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435440,
      "name": "force_dma_unencrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```
</details>
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
bool force_dma_unencrypted(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool force_dma_unencrypted(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool force_dma_unencrypted(struct device * dev)
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
