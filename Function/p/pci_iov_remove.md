# Function: <code>pci_iov_remove</code>

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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370112,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:581",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370112,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465296,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:606",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465296,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:604",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663539,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584662448,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801809,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584800624,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:786",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494689,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585493792,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:787",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419090,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585626336,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:877",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361499,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585504912,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:884",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592390652,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585972672,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:925",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594254370,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587178720,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392816,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:925",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392816,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668800,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:925",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668800,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588969440,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:927",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969440,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497069800,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497069800,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230279176,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230279176,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291111648,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291111648,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275714244,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275714244,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750546,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584749360,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681329,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584680144,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751969,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584750784,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
```

```json
{
  "name": "pci_iov_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iov_remove",
      "external": true,
      "loc": "drivers/pci/iov.c:770",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859489,
      "name": "pci_iov_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584858304,
      "name": "pci_iov_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pci_iov_remove(struct pci_dev * dev)
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
