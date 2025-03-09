# Function: <code>virt_efi_set_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008112,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:181",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008112,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586417856,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:160",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586417856,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586626848,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:168",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626848,
      "name": "virt_efi_set_variable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586627248,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586751024,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:168",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750736,
      "name": "virt_efi_set_variable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586751024,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587235696,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:168",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235376,
      "name": "virt_efi_set_variable.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071587235696,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536160,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:168",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535904,
      "name": "virt_efi_set_variable.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071587536160,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:317",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587716432,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071587721745,
      "name": "virt_efi_set_variable.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995488,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071588001441,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588203008,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071588208961,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589070448,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589076095,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589073040,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071591610966,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959072,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071591554015,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669504,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071592673849,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173568,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071594559146,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:331",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592896608,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071596318438,
      "name": "virt_efi_set_variable.cold",
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:331",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593335152,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071596847764,
      "name": "virt_efi_set_variable.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594091760,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:422",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594091760,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501558384,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501558384,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234067032,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234067032,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816928,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071587822881,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524864,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071587530705,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157536,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071588163489,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virt_efi_set_variable",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:329",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274944,
      "name": "virt_efi_set_variable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071588281313,
      "name": "virt_efi_set_variable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
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
