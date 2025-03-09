# Function: <code>xhci_pending_portevent</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586830084,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:926",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586986737,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:925",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246910,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:932",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587448288,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295648,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295648,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588333840,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:927",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333840,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588216448,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:930",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216448,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588858512,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:930",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858512,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590279792,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:967",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590279792,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591901600,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:964",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591901600,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592324912,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:808",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324912,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593066336,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:847",
      "file": "drivers/usb/host/xhci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593066336,
      "name": "xhci_pending_portevent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500583560,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233044948,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293988132,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277455494,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587154328,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586912932,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587402848,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_pending_portevent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587509246,
      "name": "xhci_pending_portevent",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:929",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool xhci_pending_portevent(struct xhci_hcd * xhci)
```
</details>
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
