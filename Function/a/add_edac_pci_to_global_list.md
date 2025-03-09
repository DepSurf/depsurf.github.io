# Function: <code>add_edac_pci_to_global_list</code>

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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586577054,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587044140,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587342524,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587520684,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587794572,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587999292,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int add_edac_pci_to_global_list(struct edac_pci_ctl_info * pci)
```

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853008,
      "name": "add_edac_pci_to_global_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071588854216,
      "name": "add_edac_pci_to_global_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int add_edac_pci_to_global_list(struct edac_pci_ctl_info * pci)
```

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868352,
      "name": "add_edac_pci_to_global_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071591594770,
      "name": "add_edac_pci_to_global_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588755324,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589446780,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590925628,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:99",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592625564,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:96",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593056172,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:96",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593807964,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:96",
      "file": "drivers/edac/edac_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_add_device"
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
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501245032,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233747964,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294779124,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277937874,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587630268,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587398284,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587955436,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_edac_pci_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588070780,
      "name": "add_edac_pci_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_pci.c:100",
      "file": "drivers/edac/edac_pci.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int add_edac_pci_to_global_list(struct edac_pci_ctl_info * pci)
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
int add_edac_pci_to_global_list(struct edac_pci_ctl_info * pci)
```
</details>
</li>
</ul>
