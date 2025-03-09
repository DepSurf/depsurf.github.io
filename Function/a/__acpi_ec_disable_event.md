# Function: <code>__acpi_ec_disable_event</code>

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
void __acpi_ec_disable_event(struct acpi_ec * ec)
```

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584037762,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:489",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584037762,
      "name": "__acpi_ec_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584097155,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:494",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584368339,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:496",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584589619,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:496",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584687027,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:496",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584887478,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:486",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585023227,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725339,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:494",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722160,
      "name": "__acpi_ec_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585732846,
      "name": "__acpi_ec_disable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585846859,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:477",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585844224,
      "name": "__acpi_ec_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071591433519,
      "name": "__acpi_ec_disable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725387,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:478",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722944,
      "name": "__acpi_ec_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071591374276,
      "name": "__acpi_ec_disable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207010,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:480",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204784,
      "name": "__acpi_ec_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071592409044,
      "name": "__acpi_ec_disable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587444906,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:501",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588705590,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:502",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588993798,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:502",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589298054,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:502",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497436156,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584965602,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584874411,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584974811,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
  "name": "__acpi_ec_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585080987,
      "name": "__acpi_ec_disable_event",
      "external": false,
      "loc": "drivers/acpi/ec.c:488",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __acpi_ec_disable_event(struct acpi_ec * ec)
```
</details>
</li>
</ul>
