# Function: <code>warn_invalid_dmar</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297280,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:821",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297280,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587846044,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:833",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644224,
      "name": "warn_invalid_dmar.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588061164,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:832",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830272,
      "name": "warn_invalid_dmar.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588287852,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:836",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920032,
      "name": "warn_invalid_dmar.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853148,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:839",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341360,
      "name": "warn_invalid_dmar.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589232424,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:839",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584000,
      "name": "warn_invalid_dmar.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589475224,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:839",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707920,
      "name": "warn_invalid_dmar.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585938124,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:828",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935744,
      "name": "warn_invalid_dmar.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586077600,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:838",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077600,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824608,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:838",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824608,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881136,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:860",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881136,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586761520,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:867",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761520,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:866",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587317200,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071592471793,
      "name": "warn_invalid_dmar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:864",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631616,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071594341630,
      "name": "warn_invalid_dmar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:865",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099552,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071596241696,
      "name": "warn_invalid_dmar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:867",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413120,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071596770146,
      "name": "warn_invalid_dmar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:867",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590757216,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071597678710,
      "name": "warn_invalid_dmar.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838720,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:838",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838720,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697760,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:838",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697760,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027616,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:838",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027616,
      "name": "warn_invalid_dmar",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```

```json
{
  "name": "warn_invalid_dmar",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135568,
      "name": "warn_invalid_dmar",
      "external": false,
      "loc": "drivers/iommu/dmar.c:838",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135568,
      "name": "warn_invalid_dmar",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void warn_invalid_dmar(u64 addr, const char * message)
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
