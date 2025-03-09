# Function: <code>get_handler_for_dbx</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596465695,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "certs/load_uefi.c:126",
      "file": "certs/load_uefi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465695,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602792533,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "certs/load_uefi.c:126",
      "file": "certs/load_uefi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602792533,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 218
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602964731,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "certs/load_uefi.c:135",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602964731,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604763729,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "certs/load_uefi.c:126",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604860708,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:135",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604763729,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071604860708,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604966431,
      "name": "get_handler_for_dbx",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:135",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604966431,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 189
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605003490,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605003490,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 189
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609283740,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609283740,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 183
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612352859,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612352859,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 183
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614494240,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:83",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614494240,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 244
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615441417,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:83",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615441417,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 244
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617239747,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:77",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617239747,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 250
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627954048,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:77",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627954048,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 243
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619717344,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:77",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619717344,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 243
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622024928,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:94",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622024928,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 243
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511047940,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511047940,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 176
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243529572,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243529572,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 192
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302723152,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302723152,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 408
    }
  ]
}
```
</details>
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908950,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908950,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 189
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604878002,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604878002,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 189
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604986122,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604986122,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 189
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_dbx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605007660,
      "name": "get_handler_for_dbx",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:73",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605007660,
      "name": "get_handler_for_dbx",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t * sig_type)
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
