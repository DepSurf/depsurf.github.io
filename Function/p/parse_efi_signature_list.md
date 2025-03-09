# Function: <code>parse_efi_signature_list</code>

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
int parse_efi_signature_list(const void * data, size_t size, struct key * keyring)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595382770,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/efi_parser.c:27",
      "file": "crypto/asymmetric_keys/efi_parser.c",
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
      "addr": 18446744071595382770,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int parse_efi_signature_list(const void * data, size_t size, struct key * keyring)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595631106,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/efi_parser.c:27",
      "file": "crypto/asymmetric_keys/efi_parser.c",
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
      "addr": 18446744071595631106,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596464254,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "certs/efi_parser.c:41",
      "file": "certs/efi_parser.c",
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
      "addr": 18446744071596464254,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602791086,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "certs/efi_parser.c:41",
      "file": "certs/efi_parser.c",
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
      "addr": 18446744071602791086,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602964067,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "certs/efi_parser.c:41",
      "file": "certs/efi_parser.c",
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
      "addr": 18446744071602964067,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604762294,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "certs/efi_parser.c:37",
      "file": "certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604762294,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604965954,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071604965954,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605001775,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071605001775,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609282182,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071609282182,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612351155,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612351155,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614492276,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614492276,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615439462,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615439462,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617237621,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617237621,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627951552,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627951552,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619714848,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619714848,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622022112,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622022112,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511046108,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446603336511046108,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243527788,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 3243527788,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302721476,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 13835058055302721476,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907235,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071604907235,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604876287,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071604876287,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604984407,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071604984407,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
```

```json
{
  "name": "parse_efi_signature_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605005945,
      "name": "parse_efi_signature_list",
      "external": true,
      "loc": "security/integrity/platform_certs/efi_parser.c:37",
      "file": "security/integrity/platform_certs/efi_parser.c",
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
      "addr": 18446744071605005945,
      "name": "parse_efi_signature_list",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int parse_efi_signature_list(const void * data, size_t size, struct key * keyring)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * source</code>
</li>
<li>
<b>Param added. </b>
<code>efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct key * keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, size, keyring</code> ➡️ <code>source, data, size, get_handler_for_guid</code>
</li>
</ul>
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
int parse_efi_signature_list(const char * source, const void * data, size_t size, efi_element_handler_t (*)(const efi_guid_t *) get_handler_for_guid)
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
