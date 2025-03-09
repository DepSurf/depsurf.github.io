# Function: <code>nvme_disable_and_flr</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375904,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3740",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375904,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584569159,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3756",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569040,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584576563,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584706023,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705904,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584713577,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585420176,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3898",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419920,
      "name": "nvme_disable_and_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071585428572,
      "name": "nvme_disable_and_flr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585420176,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585576656,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3842",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576400,
      "name": "nvme_disable_and_flr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071591407586,
      "name": "nvme_disable_and_flr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585576656,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585454599,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3864",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454480,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071591349834,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nvme_disable_and_flr(struct pci_dev * dev, bool probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585920980,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3905",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920848,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071592377133,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, bool probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3918",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118080,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071594239001,
      "name": "nvme_disable_and_flr.cold",
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
int nvme_disable_and_flr(struct pci_dev * dev, bool probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588314432,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3929",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314432,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int nvme_disable_and_flr(struct pci_dev * dev, bool probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588590480,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:4035",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588590480,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int nvme_disable_and_flr(struct pci_dev * dev, bool probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588890432,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:4062",
      "file": "drivers/pci/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890432,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496968936,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496968936,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230231420,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230231420,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291070176,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291070176,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275635888,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275635888,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584656503,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656384,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584664057,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584585655,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585536,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584593209,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584656183,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656064,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584663737,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```

```json
{
  "name": "nvme_disable_and_flr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584763879,
      "name": "nvme_disable_and_flr",
      "external": false,
      "loc": "drivers/pci/quirks.c:3821",
      "file": "drivers/pci/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763760,
      "name": "nvme_disable_and_flr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071584771433,
      "name": "nvme_disable_and_flr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int nvme_disable_and_flr(struct pci_dev * dev, int probe)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int probe</code> ➡️ <code>bool probe</code>
</li>
</ul>
</details>
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
