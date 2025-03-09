# Function: <code>qh_refresh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585343712,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:122",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343712,
      "name": "qh_refresh.isra.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740176,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:122",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740176,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585928464,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:122",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928464,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009456,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:122",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009456,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586453600,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:109",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453600,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720336,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:109",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720336,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586878464,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:109",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586878464,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:109",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587138480,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587178995,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337376,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071587379427,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_intr",
        "drivers/usb/host/ehci-hcd.c:qh_link_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194944,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071588238404,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_intr",
        "drivers/usb/host/ehci-hcd.c:qh_link_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231536,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071591559476,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114464,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071591502109,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748832,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071592602057,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:114",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590171808,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071594484959,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591787920,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:114",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591787920,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592217424,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:114",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592217424,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592958224,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:114",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592958224,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500455304,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500455304,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232917488,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232917488,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293815136,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293815136,
      "name": "qh_refresh",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277343358,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277343358,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043456,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071587085507,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291936,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071587333987,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```

```json
{
  "name": "qh_refresh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qh_refresh",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:113",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_link_async",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400432,
      "name": "qh_refresh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071587440467,
      "name": "qh_refresh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void qh_refresh(struct ehci_hcd * ehci, struct ehci_qh * qh)
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
