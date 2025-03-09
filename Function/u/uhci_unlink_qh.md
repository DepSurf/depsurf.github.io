# Function: <code>uhci_unlink_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422208,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:552",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422208,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818288,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818288,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586006992,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586006992,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586090080,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090080,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586534480,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:552",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534480,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798144,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798144,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586955616,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955616,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587214144,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071587233782,
      "name": "uhci_unlink_qh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587414400,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414400,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588281664,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281664,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316688,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316688,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199920,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199920,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588840704,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588840704,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590269024,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590269024,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591890032,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591890032,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592313424,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313424,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593054816,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593054816,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500542048,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500542048,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233002504,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233002504,
      "name": "uhci_unlink_qh",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293936928,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293936928,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277423300,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277423300,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120480,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120480,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368960,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368960,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
```

```json
{
  "name": "uhci_unlink_qh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587476576,
      "name": "uhci_unlink_qh",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:551",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476576,
      "name": "uhci_unlink_qh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
void uhci_unlink_qh(struct uhci_hcd * uhci, struct uhci_qh * qh)
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
