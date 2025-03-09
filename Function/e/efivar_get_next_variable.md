# Function: <code>efivar_get_next_variable</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
efi_status_t efivar_get_next_variable(long unsigned int * name_size, efi_char16_t * name, efi_guid_t * vendor)
```

```json
{
  "name": "efivar_get_next_variable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592883472,
      "name": "efivar_get_next_variable",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:184",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/vars.c:efivar_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592883472,
      "name": "efivar_get_next_variable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
efi_status_t efivar_get_next_variable(long unsigned int * name_size, efi_char16_t * name, efi_guid_t * vendor)
```

```json
{
  "name": "efivar_get_next_variable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593321968,
      "name": "efivar_get_next_variable",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:188",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/vars.c:efivar_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593321968,
      "name": "efivar_get_next_variable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
efi_status_t efivar_get_next_variable(long unsigned int * name_size, efi_char16_t * name, efi_guid_t * vendor)
```

```json
{
  "name": "efivar_get_next_variable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594078960,
      "name": "efivar_get_next_variable",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:196",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/vars.c:efivar_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078960,
      "name": "efivar_get_next_variable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
efi_status_t efivar_get_next_variable(long unsigned int * name_size, efi_char16_t * name, efi_guid_t * vendor)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
