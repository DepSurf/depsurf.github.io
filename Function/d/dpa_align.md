# Function: <code>dpa_align</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305184,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:566",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305184,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366304,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:696",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366304,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248256,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:696",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248256,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:714",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816576,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071592521394,
      "name": "dpa_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:695",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165872,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071594390362,
      "name": "dpa_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:705",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590717872,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071596254787,
      "name": "dpa_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:705",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591059056,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071596783395,
      "name": "dpa_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long unsigned int dpa_align(struct nd_region * nd_region)
```

```json
{
  "name": "dpa_align",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpa_align",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:707",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403760,
      "name": "dpa_align",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071597692330,
      "name": "dpa_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int dpa_align(struct nd_region * nd_region)
```
</details>
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
