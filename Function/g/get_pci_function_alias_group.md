# Function: <code>get_pci_function_alias_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584263968,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:637",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263968,
      "name": "get_pci_function_alias_group",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604976,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:628",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604976,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786640,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:779",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786640,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584875696,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:823",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875696,
      "name": "get_pci_function_alias_group",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585295232,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:825",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295232,
      "name": "get_pci_function_alias_group",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585536128,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:826",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536128,
      "name": "get_pci_function_alias_group",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585660736,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:892",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660736,
      "name": "get_pci_function_alias_group",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585887056,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1110",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887056,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586029312,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029312,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586765584,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1269",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765584,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586945152,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1301",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945152,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586826800,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1330",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826800,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587387136,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1345",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387136,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588696752,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1319",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588696752,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176464,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1440",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176464,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590498416,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1431",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590498416,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590852080,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1575",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group",
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590852080,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498827664,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498827664,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231437044,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231437044,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292042944,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292042944,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585790288,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790288,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585649472,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649472,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585979328,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979328,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
```

```json
{
  "name": "get_pci_function_alias_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586087168,
      "name": "get_pci_function_alias_group",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:pci_device_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087168,
      "name": "get_pci_function_alias_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct iommu_group * get_pci_function_alias_group(struct pci_dev * pdev, long unsigned int * devfns)
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
