# Function: <code>nsl_get_claim_class</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "nsl_get_claim_class",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587865712,
      "name": "nsl_get_claim_class",
      "external": true,
      "loc": "drivers/nvdimm/label.c:806",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865712,
      "name": "nsl_get_claim_class",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "nsl_get_claim_class",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsl_get_claim_class",
      "external": true,
      "loc": "drivers/nvdimm/label.c:859",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594394445,
      "name": "nsl_get_claim_class.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589214976,
      "name": "nsl_get_claim_class",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "nsl_get_claim_class",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsl_get_claim_class",
      "external": true,
      "loc": "drivers/nvdimm/label.c:859",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596258280,
      "name": "nsl_get_claim_class.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071590770544,
      "name": "nsl_get_claim_class",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "nsl_get_claim_class",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsl_get_claim_class",
      "external": true,
      "loc": "drivers/nvdimm/label.c:859",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596786359,
      "name": "nsl_get_claim_class.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071591111936,
      "name": "nsl_get_claim_class",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "nsl_get_claim_class",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsl_get_claim_class",
      "external": true,
      "loc": "drivers/nvdimm/label.c:859",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597695294,
      "name": "nsl_get_claim_class.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071591457264,
      "name": "nsl_get_claim_class",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata * ndd, struct nd_namespace_label * nd_label)
```
</details>
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
