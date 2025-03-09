# Function: <code>iosf_mbi_get_sem</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433952,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:233",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433952,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:224",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449440,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579450389,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453008,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579454336,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579475278,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579471422,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579473534,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579539070,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627384,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579741102,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787582,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579821361,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448848,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579450176,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377824,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579379152,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448768,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579450096,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int iosf_mbi_get_sem(u32 * sem)
```

```json
{
  "name": "iosf_mbi_get_sem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_get_sem",
      "external": false,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:247",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458320,
      "name": "iosf_mbi_get_sem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579459646,
      "name": "iosf_mbi_get_sem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
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
int iosf_mbi_get_sem(u32 * sem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iosf_mbi_get_sem(u32 * sem)
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
