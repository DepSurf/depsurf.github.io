# Function: <code>power_supply_show_usb_type</code>

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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587110197,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:81",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587288418,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:81",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587558005,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587761285,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t power_supply_show_usb_type(struct device * dev, const struct power_supply_desc * desc, union power_supply_propval * value, char * buf)
```

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:224",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588606496,
      "name": "power_supply_show_usb_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071588607682,
      "name": "power_supply_show_usb_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t power_supply_show_usb_type(struct device * dev, const struct power_supply_desc * desc, union power_supply_propval * value, char * buf)
```

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:229",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629568,
      "name": "power_supply_show_usb_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071591580528,
      "name": "power_supply_show_usb_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588514736,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:229",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589187936,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:229",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590647215,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:238",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592311631,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:238",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592737700,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:239",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593485652,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:240",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500957284,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233470816,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294416848,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277717142,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587402229,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587170437,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587717429,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
  "name": "power_supply_show_usb_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587830485,
      "name": "power_supply_show_usb_type",
      "external": false,
      "loc": "drivers/power/supply/power_supply_sysfs.c:80",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property"
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
ssize_t power_supply_show_usb_type(struct device * dev, const struct power_supply_desc * desc, union power_supply_propval * value, char * buf)
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
ssize_t power_supply_show_usb_type(struct device * dev, const struct power_supply_desc * desc, union power_supply_propval * value, char * buf)
```
</details>
</li>
</ul>
