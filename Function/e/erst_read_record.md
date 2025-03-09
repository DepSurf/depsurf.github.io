# Function: <code>erst_read_record</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header * record, size_t buflen, size_t recordlen, const guid_t * creatorid)
```

```json
{
  "name": "erst_read_record",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587880239,
      "name": "erst_read_record",
      "external": true,
      "loc": "drivers/acpi/apei/erst.c:876",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877712,
      "name": "erst_read_record",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header * record, size_t buflen, size_t recordlen, const guid_t * creatorid)
```

```json
{
  "name": "erst_read_record",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589227673,
      "name": "erst_read_record",
      "external": true,
      "loc": "drivers/acpi/apei/erst.c:876",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589227152,
      "name": "erst_read_record",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header * record, size_t buflen, size_t recordlen, const guid_t * creatorid)
```

```json
{
  "name": "erst_read_record",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589524298,
      "name": "erst_read_record",
      "external": true,
      "loc": "drivers/acpi/apei/erst.c:876",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523760,
      "name": "erst_read_record",
      "section": ".text",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header * record, size_t buflen, size_t recordlen, const guid_t * creatorid)
```

```json
{
  "name": "erst_read_record",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589832330,
      "name": "erst_read_record",
      "external": true,
      "loc": "drivers/acpi/apei/erst.c:909",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589831792,
      "name": "erst_read_record",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ssize_t erst_read_record(u64 record_id, struct cper_record_header * record, size_t buflen, size_t recordlen, const guid_t * creatorid)
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
