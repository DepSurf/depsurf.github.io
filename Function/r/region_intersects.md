# Function: <code>region_intersects</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, const char * name)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398144,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:513",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398144,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406080,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:541",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:memremap",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406080,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426384,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:541",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:memremap",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426384,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414144,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:541",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414144,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442016,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:559",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:memremap",
        "mm/hmm.c:hmm_devmem_add",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442016,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579457040,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:527",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/hmm.c:hmm_devmem_add",
        "mm/hmm.c:hmm_devmem_pages_create",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457040,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490704,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:521",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/hmm.c:hmm_devmem_add",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490704,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508560,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/resource.c:devm_request_free_mem_region",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508560,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534608,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534608,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568144,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/resource.c:__request_free_mem_region",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568144,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549488,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:543",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/resource.c:__request_free_mem_region",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549488,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553600,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:553",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553600,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626160,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:553",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626160,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718480,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:540",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718480,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847584,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:541",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847584,
      "name": "region_intersects",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897808,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:541",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897808,
      "name": "region_intersects",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936736,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:596",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:pagemap_range",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936736,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490681072,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490681072,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224753004,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224753004,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283502752,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283502752,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414850,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414850,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508272,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508272,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437072,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437072,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508192,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508192,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc)
```

```json
{
  "name": "region_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540992,
      "name": "region_intersects",
      "external": true,
      "loc": "kernel/resource.c:536",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:devmem_is_allowed",
        "kernel/iomem.c:memremap",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540992,
      "name": "region_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int desc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
