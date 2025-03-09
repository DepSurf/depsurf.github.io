# Function: <code>pcibios_sriov_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392352,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:233",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392352,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583707760,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:233",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707760,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846096,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:236",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846096,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887488,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:229",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887488,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150160,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:222",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150160,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367168,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:249",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367168,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462304,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:250",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462304,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659712,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:248",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659712,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584797872,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584797872,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585492176,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:433",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492176,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585624720,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:434",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624720,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503296,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:524",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503296,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585971008,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:531",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971008,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587176960,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:572",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176960,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390816,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:572",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390816,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588666832,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:572",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666832,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967472,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:571",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967472,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497066792,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497066792,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230276276,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230276276,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282611488,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-common.c:254",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282611488,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275711496,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275711496,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584746624,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584746624,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584677392,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677392,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748032,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748032,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
int pcibios_sriov_disable(struct pci_dev * pdev)
```

```json
{
  "name": "pcibios_sriov_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584855600,
      "name": "pcibios_sriov_disable",
      "external": true,
      "loc": "drivers/pci/iov.c:414",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:sriov_disable",
        "drivers/pci/iov.c:sriov_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855600,
      "name": "pcibios_sriov_disable",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 13
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
