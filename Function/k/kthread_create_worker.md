# Function: <code>kthread_create_worker</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539424,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:696",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539424,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526288,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:702",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526288,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552448,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:709",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552448,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579664,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:727",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579664,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616848,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:729",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616848,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641200,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641200,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667632,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667632,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701072,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:774",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701072,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679232,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:807",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679232,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685504,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:834",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685504,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763824,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:834",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763824,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869616,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:894",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869616,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012352,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:895",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012352,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065888,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:896",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065888,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108528,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:913",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_worker_init",
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108528,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490844984,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490844984,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224875648,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224875648,
      "name": "kthread_create_worker",
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283681712,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283681712,
      "name": "kthread_create_worker",
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271513806,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271513806,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643952,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643952,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572336,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572336,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641216,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641216,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675456,
      "name": "kthread_create_worker",
      "external": true,
      "loc": "kernel/kthread.c:738",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675456,
      "name": "kthread_create_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct kthread_worker * kthread_create_worker(unsigned int flags, const char * namefmt, void (anon))
```
</details>
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
