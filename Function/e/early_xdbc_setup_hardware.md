# Function: <code>early_xdbc_setup_hardware</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:21",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:22",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:22",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604972178,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:658",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604972178,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605081296,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:654",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605081296,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 654
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605120779,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:654",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605120779,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 654
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609397399,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:653",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609397399,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612468887,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:648",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612468887,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614610606,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:648",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614610606,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615568125,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:655",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615568125,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617374780,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:658",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617374780,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628114416,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:658",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628114416,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619880944,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:657",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619880944,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622190624,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:657",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622190624,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:22",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:22",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "early_xdbc_setup_hardware",
      "external": false,
      "loc": "include/linux/usb/xhci-dbgp.h:22",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int early_xdbc_setup_hardware()
```

```json
{
  "name": "early_xdbc_setup_hardware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605124973,
      "name": "early_xdbc_setup_hardware",
      "external": true,
      "loc": "drivers/usb/early/xhci-dbc.c:654",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605124973,
      "name": "early_xdbc_setup_hardware",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 654
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
int early_xdbc_setup_hardware()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
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
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int early_xdbc_setup_hardware()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
