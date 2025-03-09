# Function: <code>pcibios_release_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583263808,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1548",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573968,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1573",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710560,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884432,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1571",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884432,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373120,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1574",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373120,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587676928,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1629",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676928,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808224,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1802",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808224,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584488272,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1877",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113696,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584623856,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319392,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591139680,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1943",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139680,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591223920,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2079",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223920,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173168,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2109",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173168,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592026688,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2140",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026688,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593793712,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2200",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793712,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595736848,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2174",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595736848,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596262832,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2212",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262832,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597145488,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2309",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145488,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496867880,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230145776,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282603232,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-hotplug.c:55",
      "file": "arch/powerpc/kernel/pci-hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282603232,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275567512,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576016,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923040,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504176,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638896,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574016,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256448,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_release_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681760,
      "name": "pcibios_release_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1873",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391968,
      "name": "pcibios_release_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcibios_release_device(struct pci_dev * dev)
```
</details>
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
