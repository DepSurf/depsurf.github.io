# Function: <code>rproc_report_crash</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588238542,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588238542,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589116158,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2366",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116158,
      "name": "rproc_report_crash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071589107200,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591617652,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2468",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591617652,
      "name": "rproc_report_crash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071589106208,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591560526,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2713",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591560526,
      "name": "rproc_report_crash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071588995824,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592680725,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2742",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592680713,
      "name": "rproc_report_crash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589708976,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594566135,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2752",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594566123,
      "name": "rproc_report_crash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071591216320,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592961872,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2676",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592961872,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593412240,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2677",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593412240,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594157952,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2677",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594157952,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501696320,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501696320,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234221184,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234221184,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295132584,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295132584,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587850238,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850238,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```

```json
{
  "name": "rproc_report_crash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310878,
      "name": "rproc_report_crash",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2205",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310878,
      "name": "rproc_report_crash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void rproc_report_crash(struct rproc * rproc, enum rproc_crash_type type)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
