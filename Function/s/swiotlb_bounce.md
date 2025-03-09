# Function: <code>swiotlb_bounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583113516,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "lib/swiotlb.c:388",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "lib/swiotlb.c:swiotlb_tbl_unmap_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583408209,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "lib/swiotlb.c:388",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_unmap_single",
        "lib/swiotlb.c:swiotlb_tbl_map_single"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583533617,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "lib/swiotlb.c:418",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_unmap_single",
        "lib/swiotlb.c:swiotlb_tbl_map_single"
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570112,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "lib/swiotlb.c:418",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_unmap_single",
        "lib/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570112,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583815440,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "lib/swiotlb.c:456",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_sync_single",
        "lib/swiotlb.c:swiotlb_tbl_unmap_single",
        "lib/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815440,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947792,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:442",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947792,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996080,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:390",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996080,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039584,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039584,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088624,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088624,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149552,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:409",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149552,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130720,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:427",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130720,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135312,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:348",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135312,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:366",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278480,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071592150217,
      "name": "swiotlb_bounce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:395",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450608,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071593922855,
      "name": "swiotlb_bounce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:527",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695936,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071595993161,
      "name": "swiotlb_bounce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:500",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772656,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071596511421,
      "name": "swiotlb_bounce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void swiotlb_bounce(struct device * dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:835",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu",
        "kernel/dma/swiotlb.c:swiotlb_sync_single_for_device",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864816,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071597410950,
      "name": "swiotlb_bounce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491294888,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491294888,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284220240,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284220240,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271812254,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057824,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057824,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002672,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002672,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048896,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048896,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "swiotlb_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099648,
      "name": "swiotlb_bounce",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:408",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_sync_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099648,
      "name": "swiotlb_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t orig_addr</code>
</li>
</ul>
</details>
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir)
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
