# Function: <code>pci_set_vpd_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583536488,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/access.c:283",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535840,
      "name": "pci_set_vpd_size",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583672824,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/access.c:295",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_f0_set_size"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_chelsio_extend_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671920,
      "name": "pci_set_vpd_size",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712888,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/access.c:303",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_f0_set_size"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_chelsio_extend_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711760,
      "name": "pci_set_vpd_size",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970344,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/access.c:303",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_f0_set_size"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_chelsio_extend_vpd",
        "drivers/pci/quirks.c:quirk_chelsio_extend_vpd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969168,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242297,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240048,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584332041,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329792,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584527050,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525008,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584662170,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660128,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585346889,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:quirk_chelsio_extend_vpd",
        "drivers/pci/vpd.c:quirk_chelsio_extend_vpd",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585344320,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585498777,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:quirk_chelsio_extend_vpd",
        "drivers/pci/vpd.c:quirk_chelsio_extend_vpd",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496208,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496911236,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496908600,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230187100,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230184360,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291006232,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291002784,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275598456,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275596274,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584612634,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610592,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584542458,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540416,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584612330,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610288,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```

```json
{
  "name": "pci_set_vpd_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584720026,
      "name": "pci_set_vpd_size",
      "external": true,
      "loc": "drivers/pci/vpd.c:68",
      "file": "drivers/pci/vpd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_f0_set_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717984,
      "name": "pci_set_vpd_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int pci_set_vpd_size(struct pci_dev * dev, size_t len)
```
</details>
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
