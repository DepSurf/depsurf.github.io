# Function: <code>get_compat_sigevent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964864,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:876",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_timer_create",
        "ipc/compat_mq.c:compat_SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964864,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995408,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:876",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_timer_create",
        "ipc/compat_mq.c:compat_SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995408,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025904,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:884",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_timer_create",
        "ipc/compat_mq.c:compat_SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025904,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028368,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:439",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "ipc/mqueue.c:compat_SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028368,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075056,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:398",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "ipc/mqueue.c:compat_SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075056,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134448,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:363",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134448,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181664,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:334",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181664,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227072,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227072,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275280,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275280,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343440,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343440,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328560,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328560,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331824,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331824,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486448,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x64_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x64_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486448,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681072,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681072,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952352,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952352,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039360,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039360,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136576,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:179",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136576,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491519496,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_compat_sys_timer_create",
        "ipc/mqueue.c:__arm64_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491519496,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284485920,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_compat_sys_timer_create",
        "ipc/mqueue.c:__se_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284485920,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244080,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244080,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191632,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191632,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235328,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235328,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```

```json
{
  "name": "get_compat_sigevent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288320,
      "name": "get_compat_sigevent",
      "external": true,
      "loc": "kernel/compat.c:267",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288320,
      "name": "get_compat_sigevent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_compat_sigevent(struct sigevent * event, const struct compat_sigevent * u_event)
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
