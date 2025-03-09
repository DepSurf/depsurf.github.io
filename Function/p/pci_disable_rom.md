# Function: <code>pci_disable_rom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289072,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:50",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/rom.c:pci_map_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289072,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583600341,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:54",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600176,
      "name": "pci_disable_rom.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071583600288,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583737509,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:59",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737344,
      "name": "pci_disable_rom.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071583737456,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583779317,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:59",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779168,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071583779264,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584039445,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:59",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039296,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584039392,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236245,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236096,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584236192,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325909,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325760,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584325856,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584521094,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520928,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584521040,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584656214,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656048,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584656160,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585340169,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340016,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585493273,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493120,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372633,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372480,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585833385,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833232,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024912,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024912,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588201552,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201552,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477232,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477232,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774576,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774576,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496903860,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496903656,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336496903768,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230180248,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230180056,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 3230180176,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290996400,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290996176,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 13835058055290996320,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275592714,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275592554,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936275592628,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584606678,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606512,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584606624,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536502,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536336,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584536448,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584606374,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606208,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584606320,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_disable_rom(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584714070,
      "name": "pci_disable_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:58",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": [
        "drivers/pci/rom.c:pci_unmap_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713904,
      "name": "pci_disable_rom.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071584714016,
      "name": "pci_disable_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
