# Function: <code>ep_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581294863,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1264",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581461029,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1293",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541813,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1293",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581595175,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1430",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581739649,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1412",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907344,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1415",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907344,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989840,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1418",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989840,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1123
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125056,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125056,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202272,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202272,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441216,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1490",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441216,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494992,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1431",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494992,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527168,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1437",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527168,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843184,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1437",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843184,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1358
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402064,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1444",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402064,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986560,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1446",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986560,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215456,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1485",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215456,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1539
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430000,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1476",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430000,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1539
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
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493766480,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493766480,
      "name": "ep_insert.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227283744,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__do_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227283744,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287377776,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287377776,
      "name": "ep_insert.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1644
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273367026,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273367026,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171008,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171008,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110448,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110448,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1195
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
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```

```json
{
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161488,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161488,
      "name": "ep_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
  "name": "ep_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582236329,
      "name": "ep_insert",
      "external": false,
      "loc": "fs/eventpoll.c:1496",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
int ep_insert(struct eventpoll * ep, const struct epoll_event * event, struct file * tfile, int fd, int full_check)
```
</details>
</li>
</ul>
