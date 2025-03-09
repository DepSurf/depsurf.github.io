# Function: <code>iommu_enable_command_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584295478,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:531",
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
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584641796,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:585",
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
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584827815,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:594",
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
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917267,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:603",
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337872,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:632",
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
      "addr": 18446744071585337872,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585579216,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:632",
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
      "addr": 18446744071585579216,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585704176,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:635",
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
      "addr": 18446744071585704176,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585932064,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:623",
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
      "addr": 18446744071585932064,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586075200,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:624",
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
      "addr": 18446744071586075200,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821808,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:624",
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
      "addr": 18446744071586821808,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586880240,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:665",
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
      "addr": 18446744071586880240,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756640,
      "name": "iommu_enable_command_buffer",
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
      "addr": 18446744071586756640,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309280,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:688",
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
      "addr": 18446744071587309280,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623952,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:692",
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
      "addr": 18446744071588623952,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088432,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:774",
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
      "addr": 18446744071590088432,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590400624,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:809",
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
      "addr": 18446744071590400624,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590743168,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:822",
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
      "addr": 18446744071590743168,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585836320,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:624",
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
      "addr": 18446744071585836320,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585695360,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:624",
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
      "addr": 18446744071585695360,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586025216,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:624",
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
      "addr": 18446744071586025216,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_enable_command_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586133168,
      "name": "iommu_enable_command_buffer",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:624",
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
      "addr": 18446744071586133168,
      "name": "iommu_enable_command_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
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
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu * iommu)
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
