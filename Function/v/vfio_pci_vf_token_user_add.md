# Function: <code>vfio_pci_vf_token_user_add</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_vf_token_user_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587903040,
      "name": "vfio_pci_vf_token_user_add",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:498",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587903040,
      "name": "vfio_pci_vf_token_user_add.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_vf_token_user_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587963632,
      "name": "vfio_pci_vf_token_user_add",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:540",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963632,
      "name": "vfio_pci_vf_token_user_add.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "vfio_pci_vf_token_user_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587846048,
      "name": "vfio_pci_vf_token_user_add",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:521",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846048,
      "name": "vfio_pci_vf_token_user_add.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void vfio_pci_vf_token_user_add(struct vfio_pci_core_device * vdev, int val)
```

```json
{
  "name": "vfio_pci_vf_token_user_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448160,
      "name": "vfio_pci_vf_token_user_add",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:433",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448160,
      "name": "vfio_pci_vf_token_user_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void vfio_pci_vf_token_user_add(struct vfio_pci_core_device * vdev, int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void vfio_pci_vf_token_user_add(struct vfio_pci_core_device * vdev, int val)
```
</details>
</li>
</ul>
