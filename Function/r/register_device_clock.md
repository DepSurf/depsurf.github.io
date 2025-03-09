# Function: <code>register_device_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583596102,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:273",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583919348,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:305",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584060248,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:316",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584121929,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:360",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584393276,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:360",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584615220,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:367",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584712607,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914736,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:388",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914736,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050448,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050448,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585751776,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:384",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751776,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870896,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870896,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748656,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:392",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748656,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231264,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:393",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231264,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587469616,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:412",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587469616,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588736832,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:404",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588736832,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589024960,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:419",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589024960,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328960,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:407",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328960,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584897392,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897392,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002032,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002032,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```

```json
{
  "name": "register_device_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108208,
      "name": "register_device_clock",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:391",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108208,
      "name": "register_device_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int register_device_clock(struct acpi_device * adev, struct lpss_private_data * pdata)
```
</details>
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
