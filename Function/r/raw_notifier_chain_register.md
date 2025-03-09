# Function: <code>raw_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505872,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:register_cpu_notifier",
        "kernel/cpu.c:__register_cpu_notifier",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "drivers/extcon/extcon.c:extcon_register_interest",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505872,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519984,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__register_cpu_notifier",
        "kernel/cpu.c:register_cpu_notifier",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519984,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543632,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "net/core/dev.c:register_netdevice_notifier",
        "net/switchdev/switchdev.c:register_switchdev_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543632,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530192,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530192,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556688,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556688,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584960,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584960,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622160,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:347",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622160,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647168,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647168,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684304,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684304,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724240,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:314",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724240,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702480,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:359",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702480,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709616,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:359",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709616,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788160,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:340",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788160,
      "name": "raw_notifier_chain_register",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894832,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:404",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894832,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046112,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:404",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/char/random.c:execute_with_initialized_rng",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046112,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100016,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:410",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/char/random.c:execute_with_initialized_rng",
        "drivers/base/power/domain.c:dev_pm_genpd_add_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100016,
      "name": "raw_notifier_chain_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144832,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:410",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/pmdomain/core.c:dev_pm_genpd_add_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/char/random.c:execute_with_initialized_rng",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:__register_netdevice_notifier_net",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144832,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490859560,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_register",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490859560,
      "name": "raw_notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224879292,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224879292,
      "name": "raw_notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689536,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689536,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517858,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517858,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660624,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660624,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588976,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588976,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657888,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657888,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int raw_notifier_chain_register(struct raw_notifier_head * nh, struct notifier_block * n)
```

```json
{
  "name": "raw_notifier_chain_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691600,
      "name": "raw_notifier_chain_register",
      "external": true,
      "loc": "kernel/notifier.c:349",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier",
        "drivers/video/console/dummycon.c:dummycon_register_output_notifier",
        "drivers/xen/manage.c:xen_resume_notifier_register",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "net/core/dev.c:register_netdevice_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691600,
      "name": "raw_notifier_chain_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
