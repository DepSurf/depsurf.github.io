# Function: <code>vfio_pci_register_dev_region</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587070320,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070320,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912288,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:728",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912288,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974032,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:768",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974032,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587856416,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:750",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856416,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_core_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448256,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:610",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448256,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_core_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589848864,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:647",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589848864,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293402048,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293402048,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718240,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718240,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024880,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024880,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```

```json
{
  "name": "vfio_pci_register_dev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132048,
      "name": "vfio_pci_register_dev_region",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:665",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132048,
      "name": "vfio_pci_register_dev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
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
int vfio_pci_register_dev_region(struct vfio_pci_core_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device * vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops * ops, size_t size, u32 flags, void * data)
```
</details>
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
