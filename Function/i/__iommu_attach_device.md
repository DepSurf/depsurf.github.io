# Function: <code>__iommu_attach_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259808,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1091",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259808,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601040,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1081",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601040,
      "name": "__iommu_attach_device",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584782656,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1232",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782656,
      "name": "__iommu_attach_device",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871808,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1282",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871808,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585292576,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1283",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292576,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531952,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1284",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531952,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585656032,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1351",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656032,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585884624,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1568",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884624,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027216,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027216,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586775139,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1911",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:bus_iommu_probe"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769440,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950224,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1941",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950224,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586838083,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1962",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:bus_iommu_probe"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_deferred_attach",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828528,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587399219,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1983",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:bus_iommu_probe"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_deferred_attach",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389008,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588700736,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1961",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:__iommu_group_set_domain",
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_deferred_attach",
        "drivers/iommu/iommu.c:iommu_attach_device",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700736,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590180752,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1988",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:__iommu_group_set_domain",
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_deferred_attach",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590180752,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590502928,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_deferred_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590502928,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590857328,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2240",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_release_dma_ownership",
        "drivers/iommu/iommu.c:__iommu_release_dma_ownership",
        "drivers/iommu/iommu.c:iommu_detach_group",
        "drivers/iommu/iommu.c:iommu_detach_group",
        "drivers/iommu/iommu.c:iommu_deferred_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590857328,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498829744,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498829744,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231433332,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231433332,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292038864,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292038864,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788192,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788192,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585647376,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647376,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977232,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977232,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
```

```json
{
  "name": "__iommu_attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586084976,
      "name": "__iommu_attach_device",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1624",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084976,
      "name": "__iommu_attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
int __iommu_attach_device(struct iommu_domain * domain, struct device * dev)
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
