# Function: <code>iommu_aux_attach_device</code>

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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585889424,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2334",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889424,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032112,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032112,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768752,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2715",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768752,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586949280,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2938",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949280,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586832560,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2917",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832560,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587394416,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:3002",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394416,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498828752,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498828752,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231438992,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231438992,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292045328,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292045328,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793088,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793088,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585652272,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585652272,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982128,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982128,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "iommu_aux_attach_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090000,
      "name": "iommu_aux_attach_device",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090000,
      "name": "iommu_aux_attach_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
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
int iommu_aux_attach_device(struct iommu_domain * domain, struct device * dev)
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
