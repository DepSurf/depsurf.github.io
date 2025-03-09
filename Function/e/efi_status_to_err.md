# Function: <code>efi_status_to_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585990901,
      "name": "efi_status_to_err",
      "external": false,
      "loc": "drivers/firmware/efi/vars.c:306",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397040,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:788",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397040,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606096,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:820",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606096,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586731328,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:822",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731328,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215664,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:868",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215664,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516576,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:952",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:get_cert_list",
        "certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516576,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697088,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:999",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697088,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976256,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:1003",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976256,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588183520,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183520,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048544,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:907",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048544,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589057344,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:915",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057344,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944592,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:915",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944592,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653136,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:922",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653136,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591155472,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:936",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591155472,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592881920,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:960",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_get",
        "fs/efivarfs/vars.c:efivar_entry_size",
        "fs/efivarfs/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592881920,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593320400,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:1027",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_statfs",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_get",
        "fs/efivarfs/vars.c:efivar_entry_size",
        "fs/efivarfs/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593320400,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594076944,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:1064",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_set_get_size",
        "fs/efivarfs/vars.c:efivar_entry_get",
        "fs/efivarfs/vars.c:efivar_entry_size",
        "fs/efivarfs/vars.c:efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594076944,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501538616,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501538616,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234052940,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234052940,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587801952,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587801952,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587505376,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505376,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588138048,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138048,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int efi_status_to_err(efi_status_t status)
```

```json
{
  "name": "efi_status_to_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255568,
      "name": "efi_status_to_err",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:993",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "security/integrity/platform_certs/load_uefi.c:get_cert_list",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_get_size",
        "drivers/firmware/efi/vars.c:efivar_entry_get",
        "drivers/firmware/efi/vars.c:__efivar_entry_get",
        "drivers/firmware/efi/vars.c:efivar_entry_size",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set",
        "drivers/firmware/efi/vars.c:__efivar_entry_delete",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/capsule.c:efi_capsule_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255568,
      "name": "efi_status_to_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int efi_status_to_err(efi_status_t status)
```
</details>
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
int efi_status_to_err(efi_status_t status)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efi_status_to_err(efi_status_t status)
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
