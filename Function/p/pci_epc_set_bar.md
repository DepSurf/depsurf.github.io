# Function: <code>pci_epc_set_bar</code>

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
int pci_epc_set_bar(struct pci_epc * epc, enum pci_barno bar, dma_addr_t bar_phys, size_t size, int flags)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583899856,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:312",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899856,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int pci_epc_set_bar(struct pci_epc * epc, enum pci_barno bar, dma_addr_t bar_phys, size_t size, int flags)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163072,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:313",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163072,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381120,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:310",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381120,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473168,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:368",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473168,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668800,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668800,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807072,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807072,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499920,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:410",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499920,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632016,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:410",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632016,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511552,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:477",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511552,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585980016,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:522",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585980016,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587195584,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:522",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195584,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423056,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:522",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423056,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588700144,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:522",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700144,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589000960,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:521",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000960,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497086000,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497086000,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230291232,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230291232,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291122176,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291122176,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275719654,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275719654,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755808,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755808,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584686592,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686592,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757232,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757232,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, u8 func_no, struct pci_epf_bar * epf_bar)
```

```json
{
  "name": "pci_epc_set_bar",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864752,
      "name": "pci_epc_set_bar",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:421",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864752,
      "name": "pci_epc_set_bar",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int pci_epc_set_bar(struct pci_epc * epc, enum pci_barno bar, dma_addr_t bar_phys, size_t size, int flags)
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
<b>Param added. </b>
<code>struct pci_epf_bar * epf_bar</code>
</li>
<li>
<b>Param removed. </b>
<code>enum pci_barno bar</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t bar_phys</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
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
<code>epc, func_no, epf_bar</code> ➡️ <code>epc, func_no, vfunc_no, epf_bar</code>
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
