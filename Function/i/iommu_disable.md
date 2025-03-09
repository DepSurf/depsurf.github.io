# Function: <code>iommu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584294992,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:361",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294992,
      "name": "iommu_disable.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584641072,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:380",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_disable",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641072,
      "name": "iommu_disable.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826112,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:385",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826112,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915664,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:392",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915664,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336000,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:421",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336000,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585577328,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:421",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577328,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702064,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:424",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702064,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929440,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:409",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929440,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072576,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:410",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072576,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818288,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:410",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818288,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586876448,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:451",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876448,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586752928,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:447",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752928,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311898,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:464",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308768,
      "name": "iommu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588626586,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:468",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623376,
      "name": "iommu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590092090,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:462",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087792,
      "name": "iommu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590404826,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:470",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590400208,
      "name": "iommu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590748282,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:455",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_disable",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590743440,
      "name": "iommu_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231465392,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/omap-iommu.c:215",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_detach"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585833696,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:410",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833696,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585692736,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:410",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692736,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586022592,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:410",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022592,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void iommu_disable(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130544,
      "name": "iommu_disable",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:410",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130544,
      "name": "iommu_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_disable(struct amd_iommu * iommu)
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
