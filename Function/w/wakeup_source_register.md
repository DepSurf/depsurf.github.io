# Function: <code>wakeup_source_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584463216,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:209",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463216,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802564,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:209",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799728,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994564,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:209",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_init",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991680,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585079540,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:211",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076528,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585502884,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:211",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499936,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747685,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745600,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585880405,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:221",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878352,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct wakeup_source * wakeup_source_register(const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117494,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:205",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114496,
      "name": "wakeup_source_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262208,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262208,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031152,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:218",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031152,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114800,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:218",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114800,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001072,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:218",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001072,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587567312,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:219",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587567312,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588902128,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:219",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588902128,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590413536,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:219",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413536,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590733072,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:214",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590733072,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591095040,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:214",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591095040,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499088112,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499088112,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231636636,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231636636,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292268704,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292268704,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
  "name": "wakeup_source_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_source_register",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:130",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "wakeup_source_register",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:130",
      "file": "fs/eventpoll.c",
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025568,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025568,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871488,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871488,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212224,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212224,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
```

```json
{
  "name": "wakeup_source_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586321296,
      "name": "wakeup_source_register",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:215",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "fs/eventpoll.c:ep_create_wakeup_source",
        "drivers/base/power/wakeup.c:device_wakeup_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586321296,
      "name": "wakeup_source_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>name</code> ➡️ <code>dev, name</code>
</li>
</ul>
</details>
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
struct wakeup_source * wakeup_source_register(struct device * dev, const char * name)
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
