# Function: <code>__pci_enable_msix_range</code>

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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, unsigned int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699040,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1113",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699040,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583838661,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1130",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583880805,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1082",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584144293,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1082",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584361159,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1081",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584453712,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1087",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453712,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1360
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1115",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650512,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1347
    },
    {
      "addr": 18446744071584655715,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789792,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071584793303,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483429,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_enable_msix_range"
      ],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482624,
      "name": "__pci_enable_msix_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071585485872,
      "name": "__pci_enable_msix_range.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585483056,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585521717,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1140",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_enable_msix_range"
      ],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521232,
      "name": "__pci_enable_msix_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071591399075,
      "name": "__pci_enable_msix_range.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585521664,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585399317,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1146",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_enable_msix_range"
      ],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398832,
      "name": "__pci_enable_msix_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071591341309,
      "name": "__pci_enable_msix_range.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585399264,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585863018,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1054",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range",
        "drivers/pci/msi.c:pci_enable_msix_range"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587056176,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:921",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055712,
      "name": "__pci_enable_msix_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071594231379,
      "name": "__pci_enable_msix_range.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587056176,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240352,
      "name": "__pci_enable_msix_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:775",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240352,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588515856,
      "name": "__pci_enable_msix_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:770",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588515856,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1443
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814448,
      "name": "__pci_enable_msix_range",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:772",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/api.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814448,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1443
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497057144,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497057144,
      "name": "__pci_enable_msix_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
    },
    {
      "addr": 18446603336497058592,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230267060,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230267060,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291095040,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291095040,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1892
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275703430,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275703430,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738544,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
    },
    {
      "addr": 18446744071584742055,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669312,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071584672823,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739952,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071584743463,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```

```json
{
  "name": "__pci_enable_msix_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_enable_msix_range",
      "external": false,
      "loc": "drivers/pci/msi.c:1116",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:pci_enable_msix_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847520,
      "name": "__pci_enable_msix_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071584851031,
      "name": "__pci_enable_msix_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, const struct irq_affinity * affd)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __pci_enable_msix_range(struct pci_dev * dev, struct msix_entry * entries, int minvec, int maxvec, struct irq_affinity * affd, int flags)
```
</details>
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
