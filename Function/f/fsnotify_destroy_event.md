# Function: <code>fsnotify_destroy_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268432,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268432,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434144,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434144,
      "name": "fsnotify_destroy_event",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515264,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515264,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581569030,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568336,
      "name": "fsnotify_destroy_event.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071581568464,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581713318,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712608,
      "name": "fsnotify_destroy_event.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071581712752,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581880262,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879552,
      "name": "fsnotify_destroy_event.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071581879696,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581965030,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:70",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964320,
      "name": "fsnotify_destroy_event.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071581964464,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582097814,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097040,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071582097873,
      "name": "fsnotify_destroy_event.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582097184,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582175174,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174400,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071582174544,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582411376,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411376,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582465472,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465472,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582492400,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492400,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582806896,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_write",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806896,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583360848,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_write",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360848,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583944320,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_write",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944320,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584167648,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167648,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381808,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:50",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381808,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493730980,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493729760,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446603336493730072,
      "name": "fsnotify_destroy_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227255996,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227254948,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 3227255164,
      "name": "fsnotify_destroy_event",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287338976,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:finish_permission_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287337536,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055287337808,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273340454,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273339444,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446743936273339642,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582143910,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143136,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071582143280,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582081350,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080576,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071582080720,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582134390,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133616,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071582133760,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fsnotify_destroy_event(struct fsnotify_group * group, struct fsnotify_event * event)
```

```json
{
  "name": "fsnotify_destroy_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582207414,
      "name": "fsnotify_destroy_event",
      "external": true,
      "loc": "fs/notify/notification.c:57",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206624,
      "name": "fsnotify_destroy_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582206784,
      "name": "fsnotify_destroy_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
