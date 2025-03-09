# Function: <code>i2c_acpi_match_device</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int i2c_acpi_match_device(struct device * dev, void * data)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226128,
      "name": "i2c_acpi_match_device",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:355",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226128,
      "name": "i2c_acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586335616,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:234",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586335616,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799696,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:234",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799696,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072944,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:234",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072944,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233104,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:257",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233104,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587499856,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:279",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499856,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587702960,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:280",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702960,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588571712,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:280",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588571712,
      "name": "i2c_acpi_match_device",
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500863288,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:280",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500863288,
      "name": "i2c_acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_match_device",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:71",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_match_device",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:71",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_match_device",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:71",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587654208,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:280",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654208,
      "name": "i2c_acpi_match_device",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```

```json
{
  "name": "i2c_acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765488,
      "name": "i2c_acpi_match_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:280",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765488,
      "name": "i2c_acpi_match_device",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int i2c_acpi_match_device(struct device * dev, void * data)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct acpi_device_id * matches</code>
</li>
<li>
<b>Param added. </b>
<code>struct i2c_client * client</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>const struct acpi_device_id *</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```
</details>
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
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
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
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
const struct acpi_device_id * i2c_acpi_match_device(const struct acpi_device_id * matches, struct i2c_client * client)
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
