# Function: <code>get_handler_for_db</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596465547,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "certs/load_uefi.c:115",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465547,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 148
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602792385,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "certs/load_uefi.c:115",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602792385,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 148
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602964599,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "certs/load_uefi.c:124",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602964599,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604763597,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "certs/load_uefi.c:115",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604860576,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:123",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604763597,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071604860576,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604966299,
      "name": "get_handler_for_db",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:123",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604966299,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605003358,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605003358,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609283614,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609283614,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 126
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612352733,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612352733,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 126
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614494110,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:72",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614494110,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615441287,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:72",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615441287,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617239452,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:51",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617239452,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 140
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627953712,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:51",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627953712,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 133
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619717008,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:51",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619717008,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 133
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622024272,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:51",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622024272,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 133
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511047812,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511047812,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 128
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243529424,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243529424,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 148
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302722896,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302722896,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 256
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908818,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908818,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604877870,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604877870,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604985990,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604985990,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
```

```json
{
  "name": "get_handler_for_db",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605007528,
      "name": "get_handler_for_db",
      "external": true,
      "loc": "security/integrity/platform_certs/keyring_handler.c:62",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605007528,
      "name": "get_handler_for_db",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
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
efi_element_handler_t get_handler_for_db(const efi_guid_t * sig_type)
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
