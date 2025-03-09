# Function: <code>aer_get_device_error_info</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584398048,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398048,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593008,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593008,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584730832,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730832,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385296,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1012",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385296,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585544880,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1040",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544880,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585423200,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1040",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585423200,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585886944,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1042",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585886944,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587082192,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1047",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082192,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588269776,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1058",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269776,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588545360,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1061",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588545360,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844864,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1209",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844864,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496991888,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496991888,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230253456,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230253456,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275656636,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275656636,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680352,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680352,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584610464,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610464,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680992,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680992,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```

```json
{
  "name": "aer_get_device_error_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788688,
      "name": "aer_get_device_error_info",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:1086",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788688,
      "name": "aer_get_device_error_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int aer_get_device_error_info(struct pci_dev * dev, struct aer_err_info * info)
```
</details>
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
