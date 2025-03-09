# Function: <code>__pm_relax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465040,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:686",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_read_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_scan_ready_list",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/base/power/wakeup.c:pm_relax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465040,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801424,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:684",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc",
        "drivers/base/power/wakeup.c:pm_relax",
        "drivers/base/power/wakeup.c:wakeup_source_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801424,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584993424,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:684",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc",
        "drivers/base/power/wakeup.c:pm_relax",
        "drivers/base/power/wakeup.c:wakeup_source_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584993424,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585077824,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:684",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077824,
      "name": "__pm_relax.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071585077936,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585501216,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:685",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501216,
      "name": "__pm_relax.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071585501328,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585746000,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:684",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746000,
      "name": "__pm_relax.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071585746112,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585878752,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:690",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878752,
      "name": "__pm_relax.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071585878864,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586115200,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:674",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115200,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586115328,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263200,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263200,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586263328,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587032320,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:753",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032320,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071587032448,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587115776,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:753",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587115776,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071587115904,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587002048,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:754",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002048,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071587002176,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587568224,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:755",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568224,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071587568352,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588903136,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:755",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903136,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071588903264,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590414464,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:725",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590414464,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071590414608,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590733984,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:720",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590733984,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071590734128,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591095952,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:720",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591095952,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071591096096,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499085576,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499085576,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336499085760,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231637940,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231637940,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 3231638072,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292266256,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292266256,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055292266464,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_relax",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:174",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586026528,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026528,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586026656,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585872480,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872480,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071585872608,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213216,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213216,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586213344,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_relax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586322320,
      "name": "__pm_relax",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:694",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_unlock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586322320,
      "name": "__pm_relax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586322448,
      "name": "__pm_relax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __pm_relax(struct wakeup_source * ws)
```
</details>
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
