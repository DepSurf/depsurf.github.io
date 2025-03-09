# Function: <code>ehci_urb_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585338800,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:249",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338800,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585735040,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:253",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735040,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585923680,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:253",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923680,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008112,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:253",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008112,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452256,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:240",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452256,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717600,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:240",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717600,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875328,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:240",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875328,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587133984,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:240",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133984,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587334368,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334368,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190784,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190784,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588227376,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227376,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588110576,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588110576,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744592,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744592,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165408,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:252",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165408,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591781136,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:252",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591781136,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592204608,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:252",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204608,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592945328,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:252",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592945328,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500452408,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500452408,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232909688,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232909688,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293808800,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293808800,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277341078,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277341078,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040448,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040448,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288928,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288928,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
```

```json
{
  "name": "ehci_urb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397104,
      "name": "ehci_urb_done",
      "external": false,
      "loc": "drivers/usb/host/ehci-q.c:251",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397104,
      "name": "ehci_urb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ehci_urb_done(struct ehci_hcd * ehci, struct urb * urb, int status)
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
