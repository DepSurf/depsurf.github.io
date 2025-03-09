# Function: <code>sd_spinup_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584865036,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:1854",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585229077,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:1865",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585424307,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:1919",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509161,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2053",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585940857,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2091",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2060",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2047",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2066",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565376,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586580161,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712528,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586727506,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2094",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523536,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 958
    },
    {
      "addr": 18446744071587529075,
      "name": "sd_spinup_disk.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2138",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587587520,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 18446744071591521533,
      "name": "sd_spinup_disk.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2153",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468112,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071591463747,
      "name": "sd_spinup_disk.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2111",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043088,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071592529691,
      "name": "sd_spinup_disk.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2043",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405600,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    },
    {
      "addr": 18446744071594401089,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590979248,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2084",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590979248,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591332800,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2191",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332800,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591682336,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2236",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682336,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499622696,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499622696,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232078980,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232078980,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292941616,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292941616,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276807082,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276807082,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403008,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586417986,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279264,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586294242,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667088,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586682066,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void sd_spinup_disk(struct scsi_disk * sdkp)
```

```json
{
  "name": "sd_spinup_disk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_spinup_disk",
      "external": false,
      "loc": "drivers/scsi/sd.c:2074",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773040,
      "name": "sd_spinup_disk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586788112,
      "name": "sd_spinup_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void sd_spinup_disk(struct scsi_disk * sdkp)
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
