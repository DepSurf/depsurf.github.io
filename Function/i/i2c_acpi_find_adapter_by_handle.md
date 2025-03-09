# Function: <code>i2c_acpi_find_adapter_by_handle</code>

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
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586241100,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:360",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586333136,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": false,
      "loc": "drivers/i2c/i2c-core-acpi.c:317",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586333136,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796960,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": false,
      "loc": "drivers/i2c/i2c-core-acpi.c:317",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796960,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587070048,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": false,
      "loc": "drivers/i2c/i2c-core-acpi.c:317",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070048,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587230192,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": false,
      "loc": "drivers/i2c/i2c-core-acpi.c:340",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230192,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587496896,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:362",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496896,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587700112,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587700112,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588570055,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588568736,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588594455,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593120,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588479575,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:379",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477248,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589147943,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:411",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145568,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590599680,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:406",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590597504,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592259184,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:426",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592256832,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592684560,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:426",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592682128,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593430064,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:426",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593427568,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500860312,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500860312,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651360,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651360,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```

```json
{
  "name": "i2c_acpi_find_adapter_by_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587762640,
      "name": "i2c_acpi_find_adapter_by_handle",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:383",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587762640,
      "name": "i2c_acpi_find_adapter_by_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
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
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_adapter * i2c_acpi_find_adapter_by_handle(acpi_handle handle)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
