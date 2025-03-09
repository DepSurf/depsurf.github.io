# Function: <code>get_evtchn_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858368,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858368,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188736,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188736,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370240,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:145",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370240,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584451760,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:145",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451760,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862304,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:145",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862304,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093392,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:145",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093392,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204192,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:145",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204192,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416544,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416544,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557264,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557264,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276992,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:149",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:consume_one_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276992,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398048,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:245",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398048,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282016,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:255",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282016,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796064,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:255",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796064,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077360,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:255",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077360,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459312,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:256",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459312,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int get_evtchn_to_irq(evtchn_port_t evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758832,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:257",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758832,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498218744,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498218744,
      "name": "get_evtchn_to_irq",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318976,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:150",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318976,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507664,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507664,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int get_evtchn_to_irq(unsigned int evtchn)
```

```json
{
  "name": "get_evtchn_to_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585615680,
      "name": "get_evtchn_to_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:146",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:irq_from_evtchn",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615680,
      "name": "get_evtchn_to_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
