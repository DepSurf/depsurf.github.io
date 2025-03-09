# Function: <code>clockevents_switch_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876896,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876896,
      "name": "clockevents_switch_state",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906400,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906400,
      "name": "clockevents_switch_state",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579936848,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936848,
      "name": "clockevents_switch_state",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579944864,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944864,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990512,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990512,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580042480,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:153",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042480,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580089328,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089328,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133140,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134753,
      "name": "clockevents_switch_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580133024,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181264,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181264,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247203,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246512,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580231235,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230544,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236435,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235728,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580385667,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384912,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580603139,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602320,
      "name": "clockevents_switch_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580866643,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865696,
      "name": "clockevents_switch_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950403,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949440,
      "name": "clockevents_switch_state",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041699,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040736,
      "name": "clockevents_switch_state",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491404608,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491404608,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225401224,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225401224,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284349568,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284349568,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271883002,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271883002,
      "name": "clockevents_switch_state",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150464,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150464,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580095968,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095968,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580141536,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141536,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void clockevents_switch_state(struct clock_event_device * dev, enum clock_event_state state)
```

```json
{
  "name": "clockevents_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580193488,
      "name": "clockevents_switch_state",
      "external": true,
      "loc": "kernel/time/clockevents.c:147",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/clockevents.c:clockevents_exchange_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_setup_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193488,
      "name": "clockevents_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
