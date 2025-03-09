# Function: <code>raw_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506032,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "kernel/time/timekeeping.c:timekeeping_update",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_update_state",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506032,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520144,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_update_state",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520144,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543792,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/switchdev/switchdev.c:call_switchdev_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543792,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530352,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530352,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556848,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556848,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585120,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585120,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622320,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:398",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622320,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646832,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646832,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683968,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683968,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725216,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:365",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725216,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703344,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:407",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703344,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710480,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:407",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710480,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788704,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:388",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788704,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894720,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:452",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894720,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045984,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:452",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045984,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100848,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:458",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_off",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/base/power/domain.c:_genpd_power_on",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100848,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145664,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:458",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/pmdomain/core.c:_genpd_power_off",
        "drivers/pmdomain/core.c:_genpd_power_off",
        "drivers/pmdomain/core.c:_genpd_power_on",
        "drivers/pmdomain/core.c:_genpd_power_on",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145664,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490859200,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490859200,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224878860,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224878860,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689008,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689008,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517578,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517578,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660288,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660288,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588640,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588640,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657552,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657552,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int raw_notifier_call_chain(struct raw_notifier_head * nh, long unsigned int val, void * v)
```

```json
{
  "name": "raw_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691360,
      "name": "raw_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:400",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_update",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_putcs",
        "drivers/video/console/dummycon.c:dummycon_putc",
        "drivers/xen/manage.c:do_suspend",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:call_netdevice_notifiers_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691360,
      "name": "raw_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
