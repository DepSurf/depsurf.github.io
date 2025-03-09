# Function: <code>get_cert_list</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595270108,
      "name": "get_cert_list",
      "external": false,
      "loc": "kernel/modsign_uefi.c:28",
      "file": "kernel/modsign_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/modsign_uefi.c:load_uefi_certs",
        "kernel/modsign_uefi.c:load_uefi_certs",
        "kernel/modsign_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595270108,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 230
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595515880,
      "name": "get_cert_list",
      "external": false,
      "loc": "kernel/modsign_uefi.c:28",
      "file": "kernel/modsign_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/modsign_uefi.c:load_uefi_certs",
        "kernel/modsign_uefi.c:load_uefi_certs",
        "kernel/modsign_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595515880,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 230
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596464578,
      "name": "get_cert_list",
      "external": false,
      "loc": "certs/load_uefi.c:38",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596464578,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602791410,
      "name": "get_cert_list",
      "external": false,
      "loc": "certs/load_uefi.c:38",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602791410,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602964919,
      "name": "get_cert_list",
      "external": false,
      "loc": "certs/load_uefi.c:38",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602964919,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 337
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604762620,
      "name": "get_cert_list",
      "external": false,
      "loc": "certs/load_uefi.c:38",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs"
      ]
    },
    {
      "addr": 18446744071604860896,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:41",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604762620,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071604860896,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 318
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604966620,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:41",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604966620,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 318
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605002120,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605002120,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 334
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609282500,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609282500,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612351473,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612351473,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614492626,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614492626,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615439812,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615439812,
      "name": "get_cert_list",
      "section": ".init.text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617237957,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:64",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617237957,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 305
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627951952,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:65",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627951952,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 330
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619715248,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:65",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619715248,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 330
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622022512,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:65",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622022512,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 330
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511046460,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511046460,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 376
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243528152,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243528152,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 336
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
void * get_cert_list(u8 * key, long unsigned int keylen, uint64_t * size)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302721904,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_powerpc.c:21",
      "file": "security/integrity/platform_certs/load_powerpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs",
        "security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302721904,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 284
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907580,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907580,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 334
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604876632,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604876632,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 334
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604984752,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604984752,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 334
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
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
```

```json
{
  "name": "get_cert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605006290,
      "name": "get_cert_list",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:37",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605006290,
      "name": "get_cert_list",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 334
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
void * get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * * cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * * cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * * cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>efi_status_t * status</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * * cert_list</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, guid, size, cert_list, status</code> ➡️ <code>name, guid, size, status</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * key</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int keylen</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_char16_t * name</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_guid_t * guid</code>
</li>
<li>
<b>Param removed. </b>
<code>void * * cert_list</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_status_t * status</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int * size</code> ➡️ <code>uint64_t * size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_cert_list(efi_char16_t * name, efi_guid_t * guid, long unsigned int * size, void * * cert_list, efi_status_t * status)
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
