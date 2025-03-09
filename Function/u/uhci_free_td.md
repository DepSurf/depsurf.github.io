# Function: <code>uhci_free_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417808,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417808,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813904,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813904,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586002576,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002576,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586086224,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086224,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530608,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:125",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530608,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794368,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794368,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951232,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951232,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587211632,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587211632,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411888,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411888,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272256,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272256,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588307296,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307296,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190096,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190096,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588830768,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588830768,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590255840,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590255840,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591876272,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591876272,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592299712,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592299712,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593041056,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_result_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_result_common",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593041056,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500539360,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500539360,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232992908,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232992908,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293927648,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293927648,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277418192,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277418192,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587117968,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117968,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366448,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366448,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
```

```json
{
  "name": "uhci_free_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587473216,
      "name": "uhci_free_td",
      "external": false,
      "loc": "drivers/usb/host/uhci-q.c:124",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587473216,
      "name": "uhci_free_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void uhci_free_td(struct uhci_hcd * uhci, struct uhci_td * td)
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
