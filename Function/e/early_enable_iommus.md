# Function: <code>early_enable_iommus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584295424,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1654",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295424,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641520,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1869",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641520,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827536,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2009",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827536,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584917216,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2029",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917216,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585337968,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2182",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337968,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2183",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579312,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071585582056,
      "name": "early_enable_iommus.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2217",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704336,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071585705734,
      "name": "early_enable_iommus.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2293",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932240,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071585933680,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2313",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586075376,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071586076792,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2283",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821968,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071586824381,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2487",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880400,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071591476892,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2440",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756800,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071591417160,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2464",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310608,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071592470640,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2478",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625360,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
    },
    {
      "addr": 18446744071594340540,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2701",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090352,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
    },
    {
      "addr": 18446744071596241197,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2767",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590402784,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071596769398,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2787",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_reenable",
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590746240,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071597677846,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2313",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836496,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071585837912,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2313",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695536,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071585696952,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2313",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025392,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071586026808,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
void early_enable_iommus()
```

```json
{
  "name": "early_enable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_enable_iommus",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2313",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133344,
      "name": "early_enable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071586134760,
      "name": "early_enable_iommus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void early_enable_iommus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void early_enable_iommus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void early_enable_iommus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void early_enable_iommus()
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
