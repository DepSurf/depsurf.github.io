# Function: <code>__pm_stay_awake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463760,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:569",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_scan_ready_list",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "drivers/base/power/wakeup.c:pm_stay_awake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463760,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800160,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:567",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "drivers/base/power/wakeup.c:pm_stay_awake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800160,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584992112,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:567",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "drivers/base/power/wakeup.c:pm_stay_awake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584992112,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585078544,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:567",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078544,
      "name": "__pm_stay_awake.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585078624,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585501888,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:568",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501888,
      "name": "__pm_stay_awake.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585501968,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585746864,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:567",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746864,
      "name": "__pm_stay_awake.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585746944,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879632,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:573",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879632,
      "name": "__pm_stay_awake.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585879712,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586116080,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:557",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116080,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586116160,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263888,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263888,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586263968,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033392,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:636",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033392,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587033504,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587116848,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:636",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116848,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587116960,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587002608,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:637",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002608,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587002720,
      "name": "__pm_stay_awake",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587569011,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:638",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569456,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904279,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:638",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904768,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590415943,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:608",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590416496,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590735463,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:603",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590736016,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591097431,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:603",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_done_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591097984,
      "name": "__pm_stay_awake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499085872,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499085872,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446603336499086056,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231638368,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231638368,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3231638452,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292267504,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292267504,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 13835058055292267648,
      "name": "__pm_stay_awake",
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
  "name": "__pm_stay_awake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_stay_awake",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:170",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586027200,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027200,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586027280,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585873168,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873168,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585873248,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213904,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213904,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586213984,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
```

```json
{
  "name": "__pm_stay_awake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586323040,
      "name": "__pm_stay_awake",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:577",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586323040,
      "name": "__pm_stay_awake.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586323120,
      "name": "__pm_stay_awake",
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
void __pm_stay_awake(struct wakeup_source * ws)
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
