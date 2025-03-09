# Function: <code>vfio_msi_cap_len</code>

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
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587082926,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1155",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
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
int vfio_msi_cap_len(struct vfio_pci_device * vdev, u8 pos)
```

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587926416,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1187",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926416,
      "name": "vfio_msi_cap_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int vfio_msi_cap_len(struct vfio_pci_device * vdev, u8 pos)
```

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587987648,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1192",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987648,
      "name": "vfio_msi_cap_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int vfio_msi_cap_len(struct vfio_pci_device * vdev, u8 pos)
```

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869840,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1192",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869840,
      "name": "vfio_msi_cap_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int vfio_msi_cap_len(struct vfio_pci_core_device * vdev, u8 pos)
```

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588476304,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1192",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476304,
      "name": "vfio_msi_cap_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int vfio_msi_cap_len(struct vfio_pci_core_device * vdev, u8 pos)
```

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589879600,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1228",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589879600,
      "name": "vfio_msi_cap_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293420400,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1155",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586730846,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1155",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
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
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587037486,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1155",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
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
  "name": "vfio_msi_cap_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587144654,
      "name": "vfio_msi_cap_len",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1155",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len"
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
int vfio_msi_cap_len(struct vfio_pci_device * vdev, u8 pos)
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
int vfio_msi_cap_len(struct vfio_pci_core_device * vdev, u8 pos)
```
</details>
</li>
</ul>
