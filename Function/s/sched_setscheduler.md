# Function: <code>sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541696,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4053",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541696,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553210,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4303",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553088,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579577930,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4340",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577808,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561317,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4240",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561200,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590565,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4284",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590448,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622405,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4414",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622288,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659701,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4399",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659584,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685645,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:4836",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685520,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725077,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724928,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579768329,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5284",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768672,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579756946,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:6061",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774928,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764098,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:6362",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783536,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850738,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:7525",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877712,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579968185,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:7633",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993760,
      "name": "sched_setscheduler",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580127977,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:7775",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155248,
      "name": "sched_setscheduler",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190041,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:7884",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205632,
      "name": "sched_setscheduler",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236937,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:7945",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253952,
      "name": "sched_setscheduler",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490906932,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490906752,
      "name": "sched_setscheduler",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224921280,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224921048,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283747632,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283747456,
      "name": "sched_setscheduler",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271547506,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271547370,
      "name": "sched_setscheduler",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701989,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701840,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629141,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628992,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579693989,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693840,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setscheduler(struct task_struct * p, int policy, const struct sched_param * param)
```

```json
{
  "name": "sched_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579732426,
      "name": "sched_setscheduler",
      "external": true,
      "loc": "kernel/sched/core.c:5051",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:do_sched_setscheduler"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_thread_rt",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/powercap/idle_inject.c:idle_inject_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732272,
      "name": "sched_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
