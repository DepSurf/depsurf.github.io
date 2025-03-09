# Function: <code>iommu_aux_detach_device</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885184,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2348",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885184,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027408,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027408,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768192,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2729",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768192,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948880,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2952",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948880,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829664,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2931",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829664,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390128,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:3016",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390128,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498828576,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498828576,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231433576,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231433576,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292039216,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292039216,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788384,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788384,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585647568,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647568,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977424,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977424,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_detach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085200,
      "name": "iommu_aux_detach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2426",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085200,
      "name": "iommu_aux_detach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_aux_detach_device(struct iommu_domain * domain, struct device * dev)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
