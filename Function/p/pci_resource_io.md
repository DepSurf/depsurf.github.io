# Function: <code>pci_resource_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t pci_resource_io(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count, bool write)
```

```json
{
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280912,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1060",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280912,
      "name": "pci_resource_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583597504,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1059",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597504,
      "name": "pci_resource_io.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583734688,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1061",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734688,
      "name": "pci_resource_io.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583776658,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1214",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584036766,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1252",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584233914,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1202",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584323610,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1201",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584518458,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1202",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584654197,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585338613,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1040",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585491861,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1051",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585371653,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1079",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585831799,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1079",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587023287,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1074",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588199799,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1082",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588475527,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1082",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588772855,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1095",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496901552,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230178840,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290992320,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584604677,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584534485,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584604357,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
  "name": "pci_resource_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584712053,
      "name": "pci_resource_io",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:1055",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
ssize_t pci_resource_io(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count, bool write)
```
</details>
</li>
</ul>
