# Function: <code>ep_item_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581288180,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:796",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_read_events_proc",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl"
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
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581460591,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:801",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541375,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:801",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581594898,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:883",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735488,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:877",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735488,
      "name": "ep_item_poll.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581903536,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:879",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903536,
      "name": "ep_item_poll.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581988448,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988448,
      "name": "ep_item_poll.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124048,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124048,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201280,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201280,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
__poll_t ep_item_poll(const struct epitem * epi, poll_table * pt, int depth)
```

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439504,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:877",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439504,
      "name": "ep_item_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582493968,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:832",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493968,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582521472,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:838",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521472,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582837440,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:838",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837440,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583399200,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:845",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399200,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583985760,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:847",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985760,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584209056,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209056,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584423552,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:883",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423552,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493763080,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493763080,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
__poll_t ep_item_poll(const struct epitem * epi, poll_table * pt, int depth)
```

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227281632,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227281632,
      "name": "ep_item_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287375808,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287375808,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273364256,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273364256,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170016,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170016,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582106368,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106368,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582160496,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160496,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_item_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232528,
      "name": "ep_item_poll",
      "external": false,
      "loc": "fs/eventpoll.c:884",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_read_events_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232528,
      "name": "ep_item_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
__poll_t ep_item_poll(const struct epitem * epi, poll_table * pt, int depth)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
__poll_t ep_item_poll(const struct epitem * epi, poll_table * pt, int depth)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
__poll_t ep_item_poll(const struct epitem * epi, poll_table * pt, int depth)
```
</details>
</li>
</ul>
