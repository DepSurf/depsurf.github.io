# Function: <code>check_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584278640,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:255",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_dma_supported",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_dma_supported",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278640,
      "name": "check_device.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool check_device(struct device * dev)
```

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630432,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:410",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630432,
      "name": "check_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
bool check_device(struct device * dev)
```

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814976,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:413",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814976,
      "name": "check_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584906453,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:444",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904288,
      "name": "check_device.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585327430,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325264,
      "name": "check_device.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585568261,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:382",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566256,
      "name": "check_device.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585693285,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:392",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691344,
      "name": "check_device.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585919973,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:380",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585918560,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586064245,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:367",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062848,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813365,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:340",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801232,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872901,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:349",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858912,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586751013,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:296",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737648,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304757,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:296",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587290896,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
bool check_device(struct device * dev)
```

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588605328,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:297",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588605328,
      "name": "check_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool check_device(struct device * dev)
```

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066496,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:349",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066496,
      "name": "check_device",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590385285,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:349",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590726789,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:469",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585825221,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:367",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823824,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684405,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:367",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683008,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586014261,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:367",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012864,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "check_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586122213,
      "name": "check_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:367",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120816,
      "name": "check_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool check_device(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool check_device(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool check_device(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool check_device(struct device * dev)
```
</details>
</li>
</ul>
