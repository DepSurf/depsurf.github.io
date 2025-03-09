# Function: <code>acpi_dev_remove_driver_gpios</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583692852,
      "name": "acpi_dev_remove_driver_gpios",
      "external": false,
      "loc": "include/linux/acpi.h:961",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
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
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583949277,
      "name": "acpi_dev_remove_driver_gpios",
      "external": false,
      "loc": "include/linux/acpi.h:987",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
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
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584142333,
      "name": "acpi_dev_remove_driver_gpios",
      "external": false,
      "loc": "include/linux/acpi.h:1020",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
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
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584229933,
      "name": "acpi_dev_remove_driver_gpios",
      "external": false,
      "loc": "include/linux/acpi.h:1025",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
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
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584419661,
      "name": "acpi_dev_remove_driver_gpios",
      "external": false,
      "loc": "include/linux/acpi.h:1025",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584556045,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555952,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585229165,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:464",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229072,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585387165,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:525",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387072,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585271293,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:525",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271200,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585727549,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:579",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727376,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586907639,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:576",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903920,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588061463,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:613",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588056672,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588336046,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:618",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331280,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588630190,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:594",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625456,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496750796,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496750632,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584512973,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512880,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451101,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451008,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584507709,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507616,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_remove_driver_gpios",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584613981,
      "name": "acpi_dev_remove_driver_gpios",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:457",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613888,
      "name": "acpi_dev_remove_driver_gpios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device * adev)
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
