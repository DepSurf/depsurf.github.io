# Function: <code>fsnotify_notify_queue_is_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581268368,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268368,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581268384,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434712,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434080,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581434096,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581515861,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515200,
      "name": "fsnotify_notify_queue_is_empty.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581515216,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568981,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568320,
      "name": "fsnotify_notify_queue_is_empty.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581568416,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581713269,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712592,
      "name": "fsnotify_notify_queue_is_empty.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581712704,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581880225,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879536,
      "name": "fsnotify_notify_queue_is_empty.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581879648,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964993,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:64",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964304,
      "name": "fsnotify_notify_queue_is_empty.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581964416,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582097777,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097008,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582097136,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582175137,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174368,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582174496,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582412049,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:get_one_event",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll",
        "fs/notify/fanotify/fanotify_user.c:get_one_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411328,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582466145,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:get_one_event",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll",
        "fs/notify/fanotify/fanotify_user.c:get_one_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465424,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582493185,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503710,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515278,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582807665,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582819230,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830526,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:497",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583361715,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:640",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583372718,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:640",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385454,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:640",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583945267,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583957150,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583970894,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584168591,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180574,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584194446,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584382751,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_remove_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584394574,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408414,
      "name": "fsnotify_notify_queue_is_empty",
      "external": false,
      "loc": "include/linux/fsnotify_backend.h:641",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493730944,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493729712,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336493730008,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227255928,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227254924,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3227255104,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287338876,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287337744,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273340406,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273339424,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446743936273339584,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582143873,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143104,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582143232,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582081313,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080544,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582080672,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582134353,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133584,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582133712,
      "name": "fsnotify_notify_queue_is_empty",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_notify_queue_is_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582207379,
      "name": "fsnotify_notify_queue_is_empty",
      "external": true,
      "loc": "fs/notify/notification.c:51",
      "file": "fs/notify/notification.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206608,
      "name": "fsnotify_notify_queue_is_empty.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582206736,
      "name": "fsnotify_notify_queue_is_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group * group)
```
</details>
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
