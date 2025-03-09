# Function: <code>release_free_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586141209,
      "name": "release_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:752",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141209,
      "name": "release_free_pmem.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "release_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585078368,
      "name": "release_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:749",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078368,
      "name": "release_free_pmem.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585266288,
      "name": "release_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:820",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266288,
      "name": "release_free_pmem.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585350016,
      "name": "release_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:839",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350016,
      "name": "release_free_pmem.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585778432,
      "name": "release_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:839",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778432,
      "name": "release_free_pmem.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028112,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:839",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028112,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167280,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:842",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167280,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404960,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404960,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551776,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551776,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587337584,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:814",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337584,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399312,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:814",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399312,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281072,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:814",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281072,
      "name": "release_free_pmem",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847888,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:814",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847888,
      "name": "release_free_pmem",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202960,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:644",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202960,
      "name": "release_free_pmem",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590758032,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:641",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590758032,
      "name": "release_free_pmem",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591099488,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:641",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591099488,
      "name": "release_free_pmem",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591444624,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:646",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444624,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499441616,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499441616,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292696176,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292696176,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276666038,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276666038,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586242256,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586242256,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060624,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060624,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499744,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499744,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```

```json
{
  "name": "release_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611488,
      "name": "release_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611488,
      "name": "release_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
```
</details>
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
void release_free_pmem(struct nvdimm_bus * nvdimm_bus, struct nd_mapping * nd_mapping)
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
