# Function: <code>pci_epc_set_msi</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_epc_set_msi(struct pci_epc * epc, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583900272,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:206",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900272,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int pci_epc_set_msi(struct pci_epc * epc, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163488,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:207",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163488,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584379632,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:198",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379632,
      "name": "pci_epc_set_msi",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471504,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:198",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471504,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669232,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669232,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807504,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807504,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585500176,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:245",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500176,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632240,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:245",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632240,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511776,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:312",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511776,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585980496,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:331",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585980496,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587196112,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:331",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196112,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423616,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:331",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423616,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701536,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:331",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701536,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589002352,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:330",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002352,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497085680,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497085680,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230289052,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230289052,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291123328,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291123328,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275720060,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275720060,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756240,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756240,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687024,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687024,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757664,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757664,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int pci_epc_set_msi(struct pci_epc * epc, u8 func_no, u8 interrupts)
```

```json
{
  "name": "pci_epc_set_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865184,
      "name": "pci_epc_set_msi",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:251",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865184,
      "name": "pci_epc_set_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_epc_set_msi(struct pci_epc * epc, u8 interrupts)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, interrupts</code> ➡️ <code>epc, func_no, interrupts</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, interrupts</code> ➡️ <code>epc, func_no, vfunc_no, interrupts</code>
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
