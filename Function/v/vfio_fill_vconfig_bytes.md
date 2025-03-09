# Function: <code>vfio_fill_vconfig_bytes</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587080960,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1378",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080960,
      "name": "vfio_fill_vconfig_bytes.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924320,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1410",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924320,
      "name": "vfio_fill_vconfig_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587985344,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1415",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587985344,
      "name": "vfio_fill_vconfig_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867728,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1415",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867728,
      "name": "vfio_fill_vconfig_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int vfio_fill_vconfig_bytes(struct vfio_pci_core_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472848,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1415",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472848,
      "name": "vfio_fill_vconfig_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int vfio_fill_vconfig_bytes(struct vfio_pci_core_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589875888,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1462",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589875888,
      "name": "vfio_fill_vconfig_bytes",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
```

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293416480,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1378",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293416480,
      "name": "vfio_fill_vconfig_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    }
  ]
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586728880,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1378",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728880,
      "name": "vfio_fill_vconfig_bytes.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587035520,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1378",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035520,
      "name": "vfio_fill_vconfig_bytes.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_fill_vconfig_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587142688,
      "name": "vfio_fill_vconfig_bytes",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1378",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142688,
      "name": "vfio_fill_vconfig_bytes.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device * vdev</code> ➡️ <code>struct vfio_pci_core_device * vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_core_device * vdev, int offset, int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device * vdev, int offset, int size)
```
</details>
</li>
</ul>
