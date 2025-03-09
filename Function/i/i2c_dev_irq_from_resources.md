# Function: <code>i2c_dev_irq_from_resources</code>

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
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586319507,
      "name": "i2c_dev_irq_from_resources",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:682",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
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
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586783238,
      "name": "i2c_dev_irq_from_resources",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:693",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
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
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056065,
      "name": "i2c_dev_irq_from_resources",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:674",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
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
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587216090,
      "name": "i2c_dev_irq_from_resources",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:686",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481888,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:684",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481888,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587685152,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685152,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552960,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:699",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552960,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588578384,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:827",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578384,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462000,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:871",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462000,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130096,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:872",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130096,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579440,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:873",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579440,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592236640,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:874",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236640,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592661744,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:889",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661744,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593406944,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:892",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406944,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500844968,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500844968,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233362148,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233362148,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294307920,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294307920,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277649360,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277649360,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587636400,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636400,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```

```json
{
  "name": "i2c_dev_irq_from_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747600,
      "name": "i2c_dev_irq_from_resources",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:689",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747600,
      "name": "i2c_dev_irq_from_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_dev_irq_from_resources(const struct resource * resources, unsigned int num_resources)
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
