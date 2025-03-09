# Function: <code>clockevents_program_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877200,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:306",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877200,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579906704,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:306",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906704,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937152,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:306",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937152,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945152,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:306",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945152,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990816,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:311",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990816,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042784,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:311",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042784,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089632,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089632,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133328,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133328,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181584,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181584,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246704,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246704,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230736,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230736,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235920,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235920,
      "name": "clockevents_program_event",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592157253,
      "name": "clockevents_program_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580385104,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593932213,
      "name": "clockevents_program_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580602544,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595998504,
      "name": "clockevents_program_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580865968,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596516637,
      "name": "clockevents_program_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580949712,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597416087,
      "name": "clockevents_program_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071581041008,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491405000,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491405000,
      "name": "clockevents_program_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225401668,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225401668,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284350224,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284350224,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271883318,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271883318,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150784,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150784,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096288,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096288,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141856,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141856,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int clockevents_program_event(struct clock_event_device * dev, ktime_t expires, bool force)
```

```json
{
  "name": "clockevents_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193808,
      "name": "clockevents_program_event",
      "external": true,
      "loc": "kernel/time/clockevents.c:303",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193808,
      "name": "clockevents_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
