# Function: <code>uefi_blacklist_x509_tbs</code>

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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596465444,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "certs/load_uefi.c:72",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465444,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602792282,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "certs/load_uefi.c:72",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602792282,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602964496,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "certs/load_uefi.c:81",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602964496,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604763494,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "certs/load_uefi.c:72",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604861898,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:104",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604763494,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071604861898,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604967630,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:104",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604967630,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605003300,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605003300,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609283556,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609283556,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612352675,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612352675,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614494052,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614494052,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615441229,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615441229,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617239413,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:22",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617239413,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 39
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627953648,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:22",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627953648,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 39
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619716944,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:22",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619716944,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 39
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622024208,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:22",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622024208,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 39
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511047692,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511047692,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 60
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243529336,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243529336,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 44
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302722816,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302722816,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908760,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908760,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604877812,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604877812,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604985932,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604985932,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
```

```json
{
  "name": "uefi_blacklist_x509_tbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605007470,
      "name": "uefi_blacklist_x509_tbs",
      "external": false,
      "loc": "security/integrity/platform_certs/keyring_handler.c:43",
      "file": "security/integrity/platform_certs/keyring_handler.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605007470,
      "name": "uefi_blacklist_x509_tbs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
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
void uefi_blacklist_x509_tbs(const char * source, const void * data, size_t len)
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
