# Function: <code>register_xenstore_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583887984,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:658",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887984,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584218736,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:658",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218736,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584400160,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:658",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400160,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584482320,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:654",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482320,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892608,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:654",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892608,
      "name": "register_xenstore_notifier",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123648,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:657",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123648,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234464,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234464,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446624,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446624,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585587056,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585587056,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586308672,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308672,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586427312,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:667",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586427312,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586311408,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:733",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586311408,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586831008,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:730",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831008,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588115008,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:731",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115008,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501184,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:731",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501184,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801984,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:731",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801984,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138208,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:731",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138208,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498252664,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498252664,
      "name": "register_xenstore_notifier",
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
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348992,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:736",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348992,
      "name": "register_xenstore_notifier",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537456,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537456,
      "name": "register_xenstore_notifier",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_xenstore_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645440,
      "name": "register_xenstore_notifier",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:666",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event",
        "drivers/xen/manage.c:xen_setup_shutdown_event",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init",
        "drivers/xen/xen-balloon.c:xen_balloon_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645440,
      "name": "register_xenstore_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int register_xenstore_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int register_xenstore_notifier(struct notifier_block * nb)
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
int register_xenstore_notifier(struct notifier_block * nb)
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
