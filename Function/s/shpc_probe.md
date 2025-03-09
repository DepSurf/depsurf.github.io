# Function: <code>shpc_probe</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333408,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:273",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333408,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584428816,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428816,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584625157,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625072,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584626171,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584762853,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762768,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584763867,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454608,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071585455344,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602512,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071591413065,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480928,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071591355444,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947408,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071592383303,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151344,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071594247136,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357344,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071596210741,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:254",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588633456,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071596735893,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:254",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933728,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071597644477,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497027312,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497027312,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275685342,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275685342,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584711669,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711584,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584712683,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584642437,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642352,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584643451,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584713013,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712928,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584714027,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```

```json
{
  "name": "shpc_probe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584820597,
      "name": "shpc_probe",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:255",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584820512,
      "name": "shpc_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071584821611,
      "name": "shpc_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpc_probe(struct pci_dev * pdev, const struct pci_device_id * ent)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
