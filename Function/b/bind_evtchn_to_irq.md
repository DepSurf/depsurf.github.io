# Function: <code>bind_evtchn_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861056,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:829",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861056,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191616,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:840",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191616,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373072,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:839",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373072,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454576,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:831",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454576,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865280,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:831",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865280,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096288,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:829",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096288,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207040,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:829",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207040,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424478,
      "name": "bind_evtchn_to_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585419440,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560160,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560160,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586280400,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:844",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280400,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401472,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1210",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401472,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284240,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284240,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798912,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798912,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588080352,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080352,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589462288,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1250",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462288,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589762208,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1243",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589762208,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int bind_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098032,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1238",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098032,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498222120,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498222120,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321872,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:834",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321872,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510560,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510560,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int bind_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "bind_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618576,
      "name": "bind_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618576,
      "name": "bind_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
</li>
</ul>
</details>
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
int bind_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
