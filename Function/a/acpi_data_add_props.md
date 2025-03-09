# Function: <code>acpi_data_add_props</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584732640,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:320",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732640,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584934848,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584934848,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585070656,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070656,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585776120,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777200,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585894446,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:327",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585895616,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585771496,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:327",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772688,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586254456,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:327",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255664,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587494884,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:327",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496720,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588766052,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:335",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768928,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589055188,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:335",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057952,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589361552,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:339",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361552,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497474944,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497474944,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585000144,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000144,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915728,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915728,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585022240,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585022240,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```

```json
{
  "name": "acpi_data_add_props",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585128416,
      "name": "acpi_data_add_props",
      "external": true,
      "loc": "drivers/acpi/property.c:324",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128416,
      "name": "acpi_data_add_props",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union acpi_object * properties</code> ➡️ <code>union acpi_object * properties</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_device_properties * acpi_data_add_props(struct acpi_device_data * data, const guid_t * guid, const union acpi_object * properties)
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
