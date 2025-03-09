# Function: <code>add_key_to_revocation_list</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:160",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266047,
      "name": "add_key_to_revocation_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071581319888,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:160",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189270,
      "name": "add_key_to_revocation_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071581565312,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:259",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964356,
      "name": "add_key_to_revocation_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071581918992,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354416,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:259",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354416,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557456,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:262",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557456,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int add_key_to_revocation_list(const char * data, size_t size)
```

```json
{
  "name": "add_key_to_revocation_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582728240,
      "name": "add_key_to_revocation_list",
      "external": true,
      "loc": "certs/blacklist.c:262",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728240,
      "name": "add_key_to_revocation_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int add_key_to_revocation_list(const char * data, size_t size)
```
</details>
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
