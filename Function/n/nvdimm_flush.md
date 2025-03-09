# Function: <code>nvdimm_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067664,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:886",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067664,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585252448,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:934",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585252448,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585334432,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1035",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334432,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585762512,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1056",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585762512,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008960,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1096",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008960,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void nvdimm_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586147456,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1124",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147456,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391984,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1131",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391984,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539104,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539104,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587322944,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1179",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322944,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587384880,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1179",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384880,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587267008,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1186",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267008,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587834379,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1186",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834240,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589186494,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1071",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589186320,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590740590,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1129",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590740400,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591081950,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1129",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591081760,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591426846,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1130",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591426656,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499428072,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499428072,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292673424,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292673424,
      "name": "nvdimm_flush",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276654662,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276654662,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586229584,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229584,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047952,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/pmem.c:nd_pmem_shutdown",
        "drivers/nvdimm/pmem.c:nd_pmem_remove",
        "drivers/nvdimm/pmem.c:pmem_make_request",
        "drivers/nvdimm/pmem.c:pmem_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047952,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586487072,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586487072,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```

```json
{
  "name": "nvdimm_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586598816,
      "name": "nvdimm_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1082",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598816,
      "name": "nvdimm_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void nvdimm_flush(struct nd_region * nd_region)
```
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio * bio</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int nvdimm_flush(struct nd_region * nd_region, struct bio * bio)
```
</details>
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
