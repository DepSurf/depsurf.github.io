# Function: <code>pci_uevent_ers</code>

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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225440,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1549",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225440,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315088,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1546",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315088,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509984,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1580",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509984,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646016,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646016,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329152,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1558",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329152,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482432,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1537",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482432,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585362240,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1537",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362240,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821616,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1551",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821616,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011952,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1580",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011952,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588181952,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1586",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588181952,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588457952,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1587",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457952,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755056,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1600",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755056,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496891784,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496891784,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230169704,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230169704,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290979552,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290979552,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275584928,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275584928,
      "name": "pci_uevent_ers",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596496,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596496,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526304,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526304,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596176,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596176,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
```

```json
{
  "name": "pci_uevent_ers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584703872,
      "name": "pci_uevent_ers",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1593",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:report_resume",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected",
        "drivers/pci/pcie/err.c:report_error_detected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703872,
      "name": "pci_uevent_ers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_uevent_ers(struct pci_dev * pdev, enum pci_ers_result err_type)
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
