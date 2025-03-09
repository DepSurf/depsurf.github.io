# Function: <code>select_estimate_accuracy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int select_estimate_accuracy(struct timespec * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077120,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:73",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_sys_poll"
      ],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/select.c:do_sys_poll",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077120,
      "name": "select_estimate_accuracy.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071581077376,
      "name": "select_estimate_accuracy",
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
u64 select_estimate_accuracy(struct timespec * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581244597,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:73",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240080,
      "name": "select_estimate_accuracy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581240320,
      "name": "select_estimate_accuracy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 select_estimate_accuracy(struct timespec * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322373,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:74",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317952,
      "name": "select_estimate_accuracy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581318192,
      "name": "select_estimate_accuracy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 select_estimate_accuracy(struct timespec * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371104,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:74",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371104,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
u64 select_estimate_accuracy(struct timespec * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512608,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512608,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670352,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670352,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756656,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756656,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874288,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874288,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946544,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946544,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177392,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177392,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224592,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224592,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250640,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250640,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568480,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568480,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097696,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:76",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097696,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665888,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:76",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665888,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583883120,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:76",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883120,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090288,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:76",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090288,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493442536,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493442536,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227013072,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:do_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227013072,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286996800,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286996800,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273132042,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:do_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273132042,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915280,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915280,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852864,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852864,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906592,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906592,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
u64 select_estimate_accuracy(struct timespec64 * tv)
```

```json
{
  "name": "select_estimate_accuracy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976208,
      "name": "select_estimate_accuracy",
      "external": true,
      "loc": "fs/select.c:75",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976208,
      "name": "select_estimate_accuracy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
<code>struct timespec * tv</code> ➡️ <code>struct timespec64 * tv</code>
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
