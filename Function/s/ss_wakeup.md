# Function: <code>ss_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582144901,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:175",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:freeque",
        "ipc/msg.c:do_msgrcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582365015,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:175",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:freeque"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452240,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:178",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452240,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530992,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:178",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530992,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679888,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:179",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679888,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872960,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:196",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872960,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981008,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981008,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161968,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161968,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268032,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268032,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583595664,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:211",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595664,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583716016,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:211",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716016,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740496,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:211",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740496,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102160,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:211",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102160,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698384,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:211",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698384,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585389872,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:212",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389872,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620512,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:212",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620512,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867232,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:212",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867232,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495000984,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:freeque"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495000624,
      "name": "ss_wakeup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228412772,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:freeque"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228413528,
      "name": "ss_wakeup.constprop.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288883032,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:freeque"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288882048,
      "name": "ss_wakeup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274292304,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:freeque"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274292046,
      "name": "ss_wakeup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236768,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236768,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173920,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173920,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220800,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220800,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```

```json
{
  "name": "ss_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315856,
      "name": "ss_wakeup",
      "external": false,
      "loc": "ipc/msg.c:197",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315856,
      "name": "ss_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ss_wakeup(struct msg_queue * msq, struct wake_q_head * wake_q, bool kill)
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
