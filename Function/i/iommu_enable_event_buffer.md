# Function: <code>iommu_enable_event_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584295488,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:560",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
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
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584641854,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:614",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
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
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584827869,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:623",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
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
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917549,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:632",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337632,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:669",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337632,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585578752,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:669",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578752,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585703712,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:672",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703712,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585931600,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:660",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931600,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586074736,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:661",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586074736,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586819520,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:661",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819520,
      "name": "iommu_enable_event_buffer",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877664,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:718",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877664,
      "name": "iommu_enable_event_buffer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586754000,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:714",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754000,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309072,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:741",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309072,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623728,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:745",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623728,
      "name": "iommu_enable_event_buffer",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088192,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:827",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088192,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590399968,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:862",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590399968,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590742928,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:875",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590742928,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835856,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:661",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835856,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585694112,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:661",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694112,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586024752,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:661",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024752,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_event_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586132704,
      "name": "iommu_enable_event_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:661",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132704,
      "name": "iommu_enable_event_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```
</details>
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
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu * iommu)
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
