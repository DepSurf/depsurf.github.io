# Function: <code>pci_vpd_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583234876,
      "name": "pci_vpd_release",
      "external": false,
      "loc": "drivers/pci/pci.h:110",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_release_dev"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540912,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/access.c:609",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540912,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583677232,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/access.c:621",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677232,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583717648,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/access.c:629",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717648,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975248,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/access.c:629",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975248,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243056,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:392",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243056,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332800,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332800,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527824,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527824,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662944,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662944,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585347152,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347152,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499040,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499040,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585378016,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:357",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378016,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496912104,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496912104,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230187936,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230187936,
      "name": "pci_vpd_release",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291007408,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291007408,
      "name": "pci_vpd_release",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275599170,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275599170,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613408,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613408,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543232,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543232,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613104,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613104,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
```

```json
{
  "name": "pci_vpd_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720800,
      "name": "pci_vpd_release",
      "external": true,
      "loc": "drivers/pci/vpd.c:395",
      "file": "drivers/pci/vpd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_release_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720800,
      "name": "pci_vpd_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_vpd_release(struct pci_dev * dev)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void pci_vpd_release(struct pci_dev * dev)
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
