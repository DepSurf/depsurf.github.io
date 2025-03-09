# Function: <code>clockevents_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877120,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877120,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907355,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906624,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579937803,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937072,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945755,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945072,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991435,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990736,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580043371,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:179",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042704,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090219,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_shutdown_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089552,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133899,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133248,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580182155,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181504,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247292,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246592,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580231324,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230624,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236524,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235808,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580385756,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384992,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580603228,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602416,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580866732,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865808,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950492,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949552,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041788,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040848,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491405712,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_suspend_local",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491404888,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225402468,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225401572,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284351368,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284350048,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271883880,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271883226,
      "name": "clockevents_shutdown",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580151355,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150704,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096827,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096208,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580142427,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141776,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void clockevents_shutdown(struct clock_event_device * dev)
```

```json
{
  "name": "clockevents_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580194379,
      "name": "clockevents_shutdown",
      "external": true,
      "loc": "kernel/time/clockevents.c:171",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193728,
      "name": "clockevents_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
