# Function: <code>fsnotify_remove_queued_event</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582097024,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097024,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582097552,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582174384,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174384,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582174912,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582411904,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411824,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582466000,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465920,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582493048,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492880,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582807541,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807376,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583361561,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361360,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583945097,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944864,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584168425,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168192,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584382585,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:132",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382352,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493729736,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493729736,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336493730568,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227255080,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227255080,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3227255612,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287338496,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287338496,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273340134,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273340134,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582143120,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143120,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582143648,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582080560,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080560,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582081088,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133600,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133600,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582134128,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_remove_queued_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206720,
      "name": "fsnotify_remove_queued_event",
      "external": true,
      "loc": "fs/notify/notification.c:131",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206720,
      "name": "fsnotify_remove_queued_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582207152,
      "name": "fsnotify_remove_queued_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void fsnotify_remove_queued_event(struct fsnotify_group * group, struct fsnotify_event * event)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
