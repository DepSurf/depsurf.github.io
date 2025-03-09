# Function: <code>raw_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505936,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:unregister_cpu_notifier",
        "kernel/cpu.c:__unregister_cpu_notifier",
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_interest",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:register_netdevice_notifier",
        "net/core/dev.c:unregister_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505936,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520048,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__unregister_cpu_notifier",
        "kernel/cpu.c:unregister_cpu_notifier",
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520048,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543696,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier",
        "net/switchdev/switchdev.c:unregister_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543696,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530256,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530256,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556752,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556752,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585024,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585024,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622224,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:364",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622224,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646736,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646736,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683872,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683872,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723696,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:331",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723696,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702112,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:376",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702112,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709248,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:376",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709248,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787392,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:357",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787392,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893504,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:421",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893504,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044624,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:421",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044624,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101632,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:427",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/base/power/domain.c:dev_pm_genpd_remove_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101632,
      "name": "raw_notifier_chain_unregister",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146448,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:427",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_notifier_dev_net",
        "net/core/dev.c:unregister_netdevice_notifier_net",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146448,
      "name": "raw_notifier_chain_unregister",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490858984,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490858984,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224878708,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224878708,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283688880,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283688880,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517414,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517414,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660192,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660192,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588544,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588544,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657456,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657456,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int raw_notifier_chain_unregister(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691264,
      "name": "raw_notifier_chain_unregister",
      "external": true,
      "loc": "kernel/notifier.c:366",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "drivers/video/console/dummycon.c:dummycon_unregister_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_unregister",
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "net/core/dev.c:unregister_netdevice_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691264,
      "name": "raw_notifier_chain_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
