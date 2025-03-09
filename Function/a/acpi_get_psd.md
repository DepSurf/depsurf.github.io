# Function: <code>acpi_get_psd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584242062,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:353",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584318777,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584718186,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:365",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584945907,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:362",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585049875,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:362",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585254052,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585391940,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586097808,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097808,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218480,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:359",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218480,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093040,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:351",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093040,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590432,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:351",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590432,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587851792,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:364",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851792,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194560,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:364",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194560,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589488720,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:364",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589488720,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795664,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:367",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795664,
      "name": "acpi_get_psd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497664844,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585177460,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585119156,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585342340,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585449652,
      "name": "acpi_get_psd",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:358",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int acpi_get_psd(struct cpc_desc * cpc_ptr, acpi_handle handle)
```
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
