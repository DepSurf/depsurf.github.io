# Function: <code>virt_efi_set_variable_nonblocking</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007904,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:198",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007904,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586417552,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:176",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586417552,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586627136,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:185",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626848,
      "name": "virt_efi_set_variable_nonblocking.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586627136,
      "name": "virt_efi_set_variable_nonblocking",
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586750736,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:185",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750736,
      "name": "virt_efi_set_variable_nonblocking.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586751120,
      "name": "virt_efi_set_variable_nonblocking",
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587235376,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:185",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235376,
      "name": "virt_efi_set_variable_nonblocking.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071587235792,
      "name": "virt_efi_set_variable_nonblocking",
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587535904,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:185",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535904,
      "name": "virt_efi_set_variable_nonblocking.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071587536256,
      "name": "virt_efi_set_variable_nonblocking",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587721072,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:334",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721072,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588000768,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000768,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208288,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208288,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589075248,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589075248,
      "name": "virt_efi_set_variable_nonblocking.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589075504,
      "name": "virt_efi_set_variable_nonblocking",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589078624,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589078624,
      "name": "virt_efi_set_variable_nonblocking.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071589078848,
      "name": "virt_efi_set_variable_nonblocking",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588965088,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965088,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674624,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674624,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591179008,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591179008,
      "name": "virt_efi_set_variable_nonblocking.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071591179264,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592902368,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:348",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592902368,
      "name": "virt_efi_set_variable_nonblocking.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071592902640,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593341248,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:348",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593340960,
      "name": "virt_efi_set_variable_nonblocking.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071596848180,
      "name": "virt_efi_set_variable_nonblocking.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071593341248,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501562688,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501562688,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234070800,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234070800,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587822208,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822208,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530032,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530032,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588162816,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162816,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "virt_efi_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280608,
      "name": "virt_efi_set_variable_nonblocking",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:346",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280608,
      "name": "virt_efi_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
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
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
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
