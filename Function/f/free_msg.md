# Function: <code>free_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143920,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:171",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:alloc_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:freeque",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143920,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359968,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359968,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451328,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451328,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530128,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530128,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678720,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678720,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872256,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872256,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980304,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980304,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161232,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161232,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267296,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267296,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583594836,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595536,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715188,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715888,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739676,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740368,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101340,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102032,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584696925,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697680,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585388301,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389104,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618957,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619760,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585865677,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:alloc_msg"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866480,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494998920,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494998920,
      "name": "free_msg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228411504,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228411504,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288878928,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288878928,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274290834,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274290834,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236032,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236032,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173184,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173184,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220064,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220064,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void free_msg(struct msg_msg * msg)
```

```json
{
  "name": "free_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314304,
      "name": "free_msg",
      "external": true,
      "loc": "ipc/msgutil.c:169",
      "file": "ipc/msgutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msgutil.c:load_msg",
        "ipc/msgutil.c:load_msg",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314304,
      "name": "free_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
