# Function: <code>__pci_enable_msi_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, unsigned int flags)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699552,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1042",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors",
        "drivers/pci/msi.c:pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699552,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837744,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1062",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837744,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880016,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1022",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880016,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143504,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1022",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143504,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360320,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1022",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360320,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455472,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1020",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455472,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1055",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652288,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584655744,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788528,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584793273,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480704,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071585485811,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1080",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522768,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071591399192,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1086",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585400944,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071591341388,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:994",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860288,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
    },
    {
      "addr": 18446744071592368976,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:857",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053568,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071594231355,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588238512,
      "name": "__pci_enable_msi_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:405",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588238512,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514016,
      "name": "__pci_enable_msi_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:405",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514016,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588812608,
      "name": "__pci_enable_msi_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:406",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812608,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497055672,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497055672,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230265408,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230265408,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291093184,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291093184,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275702200,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275702200,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737280,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584742025,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668048,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584672793,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738688,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584743433,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msi_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msi_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1056",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846256,
      "name": "__pci_enable_msi_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071584851001,
      "name": "__pci_enable_msi_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __pci_enable_msi_range(struct pci_dev * dev, int minvec, int maxvec, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct irq_affinity * affd</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity * affd</code> ➡️ <code>struct irq_affinity * affd</code>
</li>
</ul>
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
