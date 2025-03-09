# Function: <code>__aer_print_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583339901,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer/aerdrv_errprint.c:139",
      "file": "drivers/pci/pcie/aer/aerdrv_errprint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583651949,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer/aerdrv_errprint.c:139",
      "file": "drivers/pci/pcie/aer/aerdrv_errprint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583789613,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer/aerdrv_errprint.c:139",
      "file": "drivers/pci/pcie/aer/aerdrv_errprint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error"
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
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583832952,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer/aerdrv_errprint.c:139",
      "file": "drivers/pci/pcie/aer/aerdrv_errprint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error"
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
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584095624,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer/aerdrv_errprint.c:139",
      "file": "drivers/pci/pcie/aer/aerdrv_errprint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297232,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:529",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:cper_print_aer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297232,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584393424,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393424,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593701,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593701,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584731530,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584731530,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386360,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:650",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386360,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591400151,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:670",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591400151,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591342380,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:670",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342380,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:672",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585883552,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071592370191,
      "name": "__aer_print_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:677",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078128,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071594232570,
      "name": "__aer_print_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264448,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:682",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264448,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588541136,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:685",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588541136,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588839536,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:674",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:pci_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839536,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496992888,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496992888,
      "name": "__aer_print_error",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230254908,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275657986,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584681441,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584611162,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584611162,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681690,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681690,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "__aer_print_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789386,
      "name": "__aer_print_error",
      "external": false,
      "loc": "drivers/pci/pcie/aer.c:717",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789386,
      "name": "__aer_print_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void __aer_print_error(struct pci_dev * dev, struct aer_err_info * info)
```
</details>
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
