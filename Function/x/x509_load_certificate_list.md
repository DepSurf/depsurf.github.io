# Function: <code>x509_load_certificate_list</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int x509_load_certificate_list(const u8 * cert_list, const long unsigned int list_size, const struct key * keyring)
```

```json
{
  "name": "x509_load_certificate_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x509_load_certificate_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_loader.c:7",
      "file": "crypto/asymmetric_keys/x509_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:load_module_cert",
        "certs/blacklist.c:load_revocation_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594093728,
      "name": "x509_load_certificate_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071585576704,
      "name": "x509_load_certificate_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int x509_load_certificate_list(const u8 * cert_list, const long unsigned int list_size, const struct key * keyring)
```

```json
{
  "name": "x509_load_certificate_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586341536,
      "name": "x509_load_certificate_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_loader.c:7",
      "file": "crypto/asymmetric_keys/x509_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:load_module_cert",
        "certs/blacklist.c:load_revocation_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586341536,
      "name": "x509_load_certificate_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int x509_load_certificate_list(const u8 * cert_list, const long unsigned int list_size, const struct key * keyring)
```

```json
{
  "name": "x509_load_certificate_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586588208,
      "name": "x509_load_certificate_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_loader.c:7",
      "file": "crypto/asymmetric_keys/x509_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:load_module_cert",
        "certs/blacklist.c:load_revocation_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586588208,
      "name": "x509_load_certificate_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int x509_load_certificate_list(const u8 * cert_list, const long unsigned int list_size, const struct key * keyring)
```

```json
{
  "name": "x509_load_certificate_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586857200,
      "name": "x509_load_certificate_list",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_loader.c:7",
      "file": "crypto/asymmetric_keys/x509_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:load_module_cert",
        "certs/blacklist.c:load_revocation_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857200,
      "name": "x509_load_certificate_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int x509_load_certificate_list(const u8 * cert_list, const long unsigned int list_size, const struct key * keyring)
```
</details>
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
