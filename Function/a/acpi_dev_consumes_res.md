# Function: <code>acpi_dev_consumes_res</code>

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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584033066,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:684",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584089420,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:684",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584360252,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:729",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584581276,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:729",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584678636,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:729",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584878796,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585014668,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
int acpi_dev_consumes_res(struct acpi_device * adev, struct resource * res)
```

```json
{
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585713504,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713504,
      "name": "acpi_dev_consumes_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int acpi_dev_consumes_res(struct acpi_device * adev, struct resource * res)
```

```json
{
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585835616,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:714",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835616,
      "name": "acpi_dev_consumes_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585715116,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:759",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586196444,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:766",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587433379,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:766",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588691251,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:903",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588979155,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:944",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589282915,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:1007",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497425744,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584958028,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584866828,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584966252,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
  "name": "acpi_dev_consumes_res",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585072428,
      "name": "acpi_dev_consumes_res",
      "external": false,
      "loc": "drivers/acpi/resource.c:721",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
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
int acpi_dev_consumes_res(struct acpi_device * adev, struct resource * res)
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
int acpi_dev_consumes_res(struct acpi_device * adev, struct resource * res)
```
</details>
</li>
</ul>
