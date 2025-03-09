# Function: <code>pci_epc_set_msix</code>

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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470976,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:258",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470976,
      "name": "pci_epc_set_msix",
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668608,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668608,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806880,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806880,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499728,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:305",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499728,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585631824,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:305",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631824,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511360,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:372",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511360,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979552,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:399",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979552,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587195024,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:399",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195024,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422464,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:399",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422464,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588699552,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:399",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699552,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589000368,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:398",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000368,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497085400,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497085400,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230288620,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230288620,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291125744,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291125744,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275721292,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275721292,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755616,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755616,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584686400,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686400,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757040,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757040,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
```

```json
{
  "name": "pci_epc_set_msix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864560,
      "name": "pci_epc_set_msix",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:311",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864560,
      "name": "pci_epc_set_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_epc_set_msix(struct pci_epc * epc, u8 func_no, u16 interrupts)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pci_barno bir</code>
</li>
<li>
<b>Param added. </b>
<code>u32 offset</code>
</li>
</ul>
</details>
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
<code>epc, func_no, interrupts, bir, offset</code> ➡️ <code>epc, func_no, vfunc_no, interrupts, bir, offset</code>
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
