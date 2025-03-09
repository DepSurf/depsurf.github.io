# Function: <code>security_msg_queue_msgrcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247968,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1068",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247968,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_msg_queue_msgrcv(struct msg_queue * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466624,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1092",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466624,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_msg_queue_msgrcv(struct msg_queue * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559088,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1113",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559088,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_msg_queue_msgrcv(struct msg_queue * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582646800,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1845",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582646800,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_msg_queue_msgrcv(struct msg_queue * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582801664,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1813",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582801664,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997584,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1217",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997584,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583109952,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1843",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109952,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296416,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1862",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296416,
      "name": "security_msg_queue_msgrcv",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401344,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401344,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741040,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2103",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741040,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861360,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2120",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861360,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887536,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2183",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887536,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584251248,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2191",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584251248,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584861552,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2202",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584861552,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585566816,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:2278",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566816,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797728,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:3807",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797728,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045664,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:3836",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045664,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495154224,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495154224,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228541744,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228541744,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289082096,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289082096,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274400730,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274400730,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583370080,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370080,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307184,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307184,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353856,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353856,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_msg_queue_msgrcv(struct kern_ipc_perm * msq, struct msg_msg * msg, struct task_struct * target, long int type, int mode)
```

```json
{
  "name": "security_msg_queue_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449040,
      "name": "security_msg_queue_msgrcv",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449040,
      "name": "security_msg_queue_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct msg_queue * msq</code> ➡️ <code>struct kern_ipc_perm * msq</code>
</li>
</ul>
</details>
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
