# Function: <code>pci_sriov_configure_simple</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584368592,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:860",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368592,
      "name": "pci_sriov_configure_simple",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584463776,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:885",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463776,
      "name": "pci_sriov_configure_simple",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584661111,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:883",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663418,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584661056,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584799271,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801689,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584799216,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585493575,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1065",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494661,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585493520,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626119,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1066",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419062,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585626064,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585504695,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1156",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361471,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585504640,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585972455,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1163",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592390624,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585972400,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587178453,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1204",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594254342,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587178400,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588392432,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1204",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392432,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588668416,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1204",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668416,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969056,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1206",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969056,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497068304,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497068304,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230277704,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230277704,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291111120,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291111120,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275712866,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275712866,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584748023,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750425,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584747968,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584678791,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681209,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584678736,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584749431,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751849,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584749376,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "pci_sriov_configure_simple",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584856942,
      "name": "pci_sriov_configure_simple",
      "external": true,
      "loc": "drivers/pci/iov.c:1049",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859369,
      "name": "pci_sriov_configure_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584856896,
      "name": "pci_sriov_configure_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_sriov_configure_simple(struct pci_dev * dev, int nr_virtfn)
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
