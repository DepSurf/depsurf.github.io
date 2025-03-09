# Function: <code>kill_pid_usb_asyncio</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548176,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1500",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548176,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574304,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574304,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608336,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_remove",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608336,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588528,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1506",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_remove",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588528,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595696,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1508",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595696,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667056,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1534",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667056,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766480,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1535",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766480,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898048,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1536",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898048,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947552,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1542",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947552,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986944,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1548",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986944,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490736792,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490736792,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224789012,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224789012,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283560560,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283560560,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271445360,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271445360,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550608,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550608,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479328,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479328,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547888,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547888,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
```

```json
{
  "name": "kill_pid_usb_asyncio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580960,
      "name": "kill_pid_usb_asyncio",
      "external": true,
      "loc": "kernel/signal.c:1505",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580960,
      "name": "kill_pid_usb_asyncio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid * pid, const struct cred * cred)
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
