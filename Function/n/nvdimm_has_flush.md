# Function: <code>nvdimm_has_flush</code>

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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067840,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:921",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067840,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585252624,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:969",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585252624,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585338847,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1070",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334608,
      "name": "nvdimm_has_flush",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585767039,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1091",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585762688,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586013525,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1131",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009136,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586152053,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1159",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147632,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586387312,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1185",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383200,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586535064,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530800,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587313341,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1233",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312176,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587375277,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1233",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374144,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587258124,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1240",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256144,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587828396,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1240",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823216,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179269,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1125",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173328,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590726064,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1183",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590726064,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067392,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1183",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067392,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591412128,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1184",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412128,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499423348,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499417504,
      "name": "nvdimm_has_flush",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292667260,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292661472,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276645756,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276645756,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586225544,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221280,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586043912,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable",
        "drivers/nvdimm/pmem.c:pmem_attach_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039648,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586483032,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586478768,
      "name": "nvdimm_has_flush",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int nvdimm_has_flush(struct nd_region * nd_region)
```

```json
{
  "name": "nvdimm_has_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586594776,
      "name": "nvdimm_has_flush",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:1136",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:deep_flush_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590384,
      "name": "nvdimm_has_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int nvdimm_has_flush(struct nd_region * nd_region)
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
int nvdimm_has_flush(struct nd_region * nd_region)
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
