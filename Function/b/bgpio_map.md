# Function: <code>bgpio_map</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586916411,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:666",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
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
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588071355,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:666",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
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
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588345899,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:666",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
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
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588640396,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:670",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496762376,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:649",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496762376,
      "name": "bgpio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230040068,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:649",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230040068,
      "name": "bgpio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290851824,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:649",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290851824,
      "name": "bgpio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275505212,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:649",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275505212,
      "name": "bgpio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```

```json
{
  "name": "bgpio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524160,
      "name": "bgpio_map",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:649",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524160,
      "name": "bgpio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
void * bgpio_map(struct platform_device * pdev, const char * name, resource_size_t sane_sz)
```
</details>
</li>
</ul>
