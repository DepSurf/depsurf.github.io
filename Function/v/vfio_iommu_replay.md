# Function: <code>vfio_iommu_replay</code>

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
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587058037,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1187",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888672,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1422",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888672,
      "name": "vfio_iommu_replay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587952560,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1449",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587952560,
      "name": "vfio_iommu_replay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587832224,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1697",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832224,
      "name": "vfio_iommu_replay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1698",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439648,
      "name": "vfio_iommu_replay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
    },
    {
      "addr": 18446744071592549416,
      "name": "vfio_iommu_replay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1696",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837168,
      "name": "vfio_iommu_replay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
    },
    {
      "addr": 18446744071594428229,
      "name": "vfio_iommu_replay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586705957,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1187",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
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
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587012597,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1187",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
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
  "name": "vfio_iommu_replay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587119765,
      "name": "vfio_iommu_replay",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1187",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
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
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_iommu_replay(struct vfio_iommu * iommu, struct vfio_domain * domain)
```
</details>
</li>
</ul>
