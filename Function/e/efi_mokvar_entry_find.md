# Function: <code>efi_mokvar_entry_find</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589079504,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:243",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589079504,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
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
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965904,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965904,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589675456,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589675456,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591179984,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/machine_keyring.c:trust_moklist",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591179984,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592903472,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/machine_keyring.c:trust_moklist",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592903472,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593342080,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/machine_keyring.c:trust_moklist",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593342080,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```

```json
{
  "name": "efi_mokvar_entry_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594095760,
      "name": "efi_mokvar_entry_find",
      "external": true,
      "loc": "drivers/firmware/efi/mokvar-table.c:246",
      "file": "drivers/firmware/efi/mokvar-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/machine_keyring.c:imputed_trust_enabled",
        "security/integrity/platform_certs/load_uefi.c:load_moklist_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095760,
      "name": "efi_mokvar_entry_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct efi_mokvar_table_entry * efi_mokvar_entry_find(const char * name)
```
</details>
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
