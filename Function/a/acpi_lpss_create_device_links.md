# Function: <code>acpi_lpss_create_device_links</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:557",
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
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:595",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:592",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:617",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:595",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:602",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585750464,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:603",
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
      "addr": 18446744071585750464,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233152,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:604",
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
      "addr": 18446744071586233152,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471696,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:626",
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
      "addr": 18446744071587471696,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588739056,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:618",
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
      "addr": 18446744071588739056,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589027232,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:633",
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
      "addr": 18446744071589027232,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
```

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589331648,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:598",
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
      "addr": 18446744071589331648,
      "name": "acpi_lpss_create_device_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:617",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:617",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_lpss_create_device_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_create_device_links",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:617",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void acpi_lpss_create_device_links(struct acpi_device * adev, struct platform_device * pdev)
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
