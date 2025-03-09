# Function: <code>vfio_pci_validate_vf_token</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device * vdev, bool vf_token, uuid_t * uuid)
```

```json
{
  "name": "vfio_pci_validate_vf_token",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_validate_vf_token",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587903568,
      "name": "vfio_pci_validate_vf_token",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
    },
    {
      "addr": 18446744071587912995,
      "name": "vfio_pci_validate_vf_token.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int vfio_pci_validate_vf_token(struct vfio_pci_device * vdev, bool vf_token, uuid_t * uuid)
```

```json
{
  "name": "vfio_pci_validate_vf_token",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_validate_vf_token",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1740",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964976,
      "name": "vfio_pci_validate_vf_token",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071591534801,
      "name": "vfio_pci_validate_vf_token.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device * vdev, bool vf_token, uuid_t * uuid)
```

```json
{
  "name": "vfio_pci_validate_vf_token",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_validate_vf_token",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1737",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846976,
      "name": "vfio_pci_validate_vf_token",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071591477087,
      "name": "vfio_pci_validate_vf_token.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_core_device * vdev, bool vf_token, uuid_t * uuid)
```

```json
{
  "name": "vfio_pci_validate_vf_token",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_validate_vf_token",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:1541",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453088,
      "name": "vfio_pci_validate_vf_token",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071592550331,
      "name": "vfio_pci_validate_vf_token.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_core_device * vdev, bool vf_token, uuid_t * uuid)
```

```json
{
  "name": "vfio_pci_validate_vf_token",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_validate_vf_token",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:1571",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589854912,
      "name": "vfio_pci_validate_vf_token",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071594429775,
      "name": "vfio_pci_validate_vf_token.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device * vdev, bool vf_token, uuid_t * uuid)
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
int vfio_pci_validate_vf_token(struct vfio_pci_core_device * vdev, bool vf_token, uuid_t * uuid)
```
</details>
</li>
</ul>
