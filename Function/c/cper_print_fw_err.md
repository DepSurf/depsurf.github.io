# Function: <code>cper_print_fw_err</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cper_print_fw_err(const char * pfx, struct acpi_hest_generic_data * gdata, const struct cper_sec_fw_err_rec_ref * fw_err)
```

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589065191,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:416",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589065191,
      "name": "cper_print_fw_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void cper_print_fw_err(const char * pfx, struct acpi_hest_generic_data * gdata, const struct cper_sec_fw_err_rec_ref * fw_err)
```

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591608191,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:430",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608191,
      "name": "cper_print_fw_err",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591553454,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:428",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592673193,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:427",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594558151,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:455",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592892752,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:459",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593331328,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:459",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_fw_err",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594088536,
      "name": "cper_print_fw_err",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:459",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cper_print_fw_err(const char * pfx, struct acpi_hest_generic_data * gdata, const struct cper_sec_fw_err_rec_ref * fw_err)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void cper_print_fw_err(const char * pfx, struct acpi_hest_generic_data * gdata, const struct cper_sec_fw_err_rec_ref * fw_err)
```
</details>
</li>
</ul>
