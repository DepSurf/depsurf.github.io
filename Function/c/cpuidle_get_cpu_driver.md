# Function: <code>cpuidle_get_cpu_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585906352,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:338",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906352,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305920,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:338",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305920,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513776,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:339",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513776,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586639408,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:340",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639408,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120896,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:308",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120896,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420464,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:308",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420464,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587601072,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:308",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587601072,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877872,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:308",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877872,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588083616,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083616,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588945312,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:338",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945312,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957552,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:338",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957552,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588845952,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:342",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845952,
      "name": "cpuidle_get_cpu_driver",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589544272,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:342",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589544272,
      "name": "cpuidle_get_cpu_driver",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591037168,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:342",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_enable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591037168,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592748368,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:342",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_enable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592748368,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593183024,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:346",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_enable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593183024,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593936848,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:346",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_disable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_enable_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593936848,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501327648,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/cpuidle/cpuidle-arm.c:arm_idle_init",
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501327648,
      "name": "cpuidle_get_cpu_driver",
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233817944,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/cpuidle/cpuidle-arm.c:arm_idle_init",
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233817944,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294872320,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294872320,
      "name": "cpuidle_get_cpu_driver",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuidle_get_cpu_driver",
      "external": false,
      "loc": "include/linux/cpuidle.h:200",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705408,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705408,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483696,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483696,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588039760,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039760,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
```

```json
{
  "name": "cpuidle_get_cpu_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588155376,
      "name": "cpuidle_get_cpu_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:332",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_register_device",
        "drivers/cpuidle/cpuidle.c:__cpuidle_unregister_device",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155376,
      "name": "cpuidle_get_cpu_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpuidle_driver * cpuidle_get_cpu_driver(struct cpuidle_device * dev)
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
