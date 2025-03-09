# Function: <code>edac_pci_main_kobj_setup</code>

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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586579654,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587046742,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587344853,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587523013,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587796853,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588001573,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int edac_pci_main_kobj_setup()
```

```json
{
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588855536,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855536,
      "name": "edac_pci_main_kobj_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int edac_pci_main_kobj_setup()
```

```json
{
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588870688,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588870688,
      "name": "edac_pci_main_kobj_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588757605,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589449061,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590927925,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:338",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592628661,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:338",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593059285,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:338",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593811125,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:338",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501248268,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233750896,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294783276,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277940362,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587632549,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587400533,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587957717,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
  "name": "edac_pci_main_kobj_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588073061,
      "name": "edac_pci_main_kobj_setup",
      "external": false,
      "loc": "drivers/edac/edac_pci_sysfs.c:336",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
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
int edac_pci_main_kobj_setup()
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
int edac_pci_main_kobj_setup()
```
</details>
</li>
</ul>
