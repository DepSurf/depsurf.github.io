# Function: <code>acpi_can_fallback_to_crs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518224,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:960",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518224,
      "name": "acpi_can_fallback_to_crs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583657097,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1099",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655056,
      "name": "acpi_can_fallback_to_crs.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071583659184,
      "name": "acpi_can_fallback_to_crs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583699118,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1205",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699312,
      "name": "acpi_can_fallback_to_crs",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583955571,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1134",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955760,
      "name": "acpi_can_fallback_to_crs",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584149058,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1189",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149232,
      "name": "acpi_can_fallback_to_crs",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236712,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1212",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236880,
      "name": "acpi_can_fallback_to_crs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426488,
      "name": "acpi_can_fallback_to_crs",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1268",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426656,
      "name": "acpi_can_fallback_to_crs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584563256,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585236264,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:809",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585394472,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:843",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278600,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:843",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585735172,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:897",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586912267,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:882",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588065915,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:962",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588340462,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:964",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588634750,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:941",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496759016,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584520184,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584458312,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584514920,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
  "name": "acpi_can_fallback_to_crs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584621192,
      "name": "acpi_can_fallback_to_crs",
      "external": false,
      "loc": "drivers/gpio/gpiolib-acpi.c:802",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device * adev, const char * con_id)
```
</details>
</li>
</ul>
