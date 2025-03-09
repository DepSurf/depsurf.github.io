# Function: <code>__acpi_power_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583598763,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:225",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
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
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583925065,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:225",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
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
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584066097,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:225",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
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
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584128750,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:226",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
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
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584396080,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:226",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396080,
      "name": "__acpi_power_on.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618848,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:226",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618848,
      "name": "__acpi_power_on.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584717344,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:248",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717344,
      "name": "__acpi_power_on.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919152,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919152,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054960,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054960,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758384,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:351",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758384,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585877472,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:351",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877472,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585754768,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:349",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585754768,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237744,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:361",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_power_on_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237744,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587476720,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:361",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_on_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476720,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744288,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:361",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_on_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744288,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589032688,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:362",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_on_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032688,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589337248,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:362",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_on_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337248,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497461248,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_enable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497461248,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986224,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_enable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986224,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901808,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_enable_wakeup_device_power",
        "drivers/acpi/power.c:acpi_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901808,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585006544,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585006544,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "__acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112720,
      "name": "__acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:353",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112720,
      "name": "__acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __acpi_power_on(struct acpi_power_resource * resource)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __acpi_power_on(struct acpi_power_resource * resource)
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
