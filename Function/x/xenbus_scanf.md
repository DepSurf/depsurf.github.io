# Function: <code>xenbus_scanf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881712,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:545",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881712,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212320,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:540",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212320,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584393696,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:540",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393696,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476928,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:557",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476928,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887344,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:560",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887344,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118416,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:562",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118416,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585229184,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:562",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229184,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441344,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:565",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441344,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585581776,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581776,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304112,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304112,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422832,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422832,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586306400,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306400,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826000,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826000,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109440,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109440,
      "name": "xenbus_scanf",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495024,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495024,
      "name": "xenbus_scanf",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795824,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795824,
      "name": "xenbus_scanf",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132048,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132048,
      "name": "xenbus_scanf",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498246088,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498246088,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343808,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343808,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532176,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532176,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_scanf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640176,
      "name": "xenbus_scanf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/cpu_hotplug.c:vcpu_online",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/xen/xen-balloon.c:watch_target",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640176,
      "name": "xenbus_scanf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
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
int xenbus_scanf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
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
