# Function: <code>scan_isoc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585372141,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2380",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585768637,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2380",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585957277,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2379",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586042215,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2379",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586486439,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2366",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586748663,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2367",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586895175,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587153248,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153248,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1965
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353648,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353648,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1965
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588226000,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588226000,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262640,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2355",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262640,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588143280,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2355",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143280,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781120,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2355",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781120,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212432,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2353",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212432,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591829744,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2353",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591829744,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592252656,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2353",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252656,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592993744,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2354",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592993744,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500475352,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500475352,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232932220,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232932220,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1812
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293849920,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293849920,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2232
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277359018,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277359018,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1506
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587059728,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059728,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1965
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308208,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308208,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1965
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
void scan_isoc(struct ehci_hcd * ehci)
```

```json
{
  "name": "scan_isoc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587417472,
      "name": "scan_isoc",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2363",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417472,
      "name": "scan_isoc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1965
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void scan_isoc(struct ehci_hcd * ehci)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void scan_isoc(struct ehci_hcd * ehci)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
