# Function: <code>vfio_pci_set_power_state</code>

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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066768,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:230",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066768,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587908736,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:239",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908736,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970384,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:281",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970384,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587852032,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:281",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_remove",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852032,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int vfio_pci_set_power_state(struct vfio_pci_core_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:210",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592550609,
      "name": "vfio_pci_set_power_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588458336,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int vfio_pci_set_power_state(struct vfio_pci_core_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:214",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_hot_reset",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594429961,
      "name": "vfio_pci_set_power_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589856000,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293396608,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:230",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293396608,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714688,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:230",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714688,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021328,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:230",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021328,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```

```json
{
  "name": "vfio_pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128496,
      "name": "vfio_pci_set_power_state",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:230",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128496,
      "name": "vfio_pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
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
int vfio_pci_set_power_state(struct vfio_pci_core_device * vdev, pci_power_t state)
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
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
int vfio_pci_set_power_state(struct vfio_pci_device * vdev, pci_power_t state)
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
