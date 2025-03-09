# Function: <code>ehci_enable_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340064,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:84",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340064,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585735248,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:85",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735248,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585928896,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:85",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928896,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586011904,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:85",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011904,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586456048,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586456048,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586721056,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721056,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586880640,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880640,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587139104,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139104,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587339488,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587339488,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588225038,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194384,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588261678,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230976,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588142318,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114160,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588780046,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746480,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071592601771,
      "name": "ehci_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590211322,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590171040,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071594484934,
      "name": "ehci_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591828602,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591787312,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071596299045,
      "name": "ehci_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592251419,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210768,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071596828746,
      "name": "ehci_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592992507,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592951568,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071597752411,
      "name": "ehci_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500457272,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500457272,
      "name": "ehci_enable_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232915040,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232915040,
      "name": "ehci_enable_event",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293816144,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293816144,
      "name": "ehci_enable_event",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277347038,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277347038,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587045568,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045568,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294048,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294048,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
```

```json
{
  "name": "ehci_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587403312,
      "name": "ehci_enable_event",
      "external": false,
      "loc": "drivers/usb/host/ehci-timer.c:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587403312,
      "name": "ehci_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void ehci_enable_event(struct ehci_hcd * ehci, unsigned int event, bool resched)
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
