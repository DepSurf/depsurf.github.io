# Function: <code>serial8250_clear_fifos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584116000,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:497",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116000,
      "name": "serial8250_clear_fifos.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451363,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:518",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449776,
      "name": "serial8250_clear_fifos.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633650,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:519",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632064,
      "name": "serial8250_clear_fifos.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void serial8250_clear_fifos(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584711040,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:535",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711040,
      "name": "serial8250_clear_fifos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void serial8250_clear_fifos(struct uart_8250_port * p)
```

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123824,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:552",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123824,
      "name": "serial8250_clear_fifos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585370136,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:553",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362336,
      "name": "serial8250_clear_fifos.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585493782,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:553",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486528,
      "name": "serial8250_clear_fifos.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585700303,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:561",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699952,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585841215,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840864,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586574558,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:550",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:do_set_rxtrig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:do_set_rxtrig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573056,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586684766,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:551",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:do_set_rxtrig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:do_set_rxtrig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683264,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586568751,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:555",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566832,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587109213,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:556",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107120,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588415765,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:543",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588413104,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589842981,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:543",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840080,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590151716,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:483",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149088,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590491908,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:484",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590489232,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498572520,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498572144,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231208108,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231207752,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291788492,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291788000,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276176166,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276175874,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585602223,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601872,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585467311,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466960,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585791615,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791264,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serial8250_clear_fifos",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899327,
      "name": "serial8250_clear_fifos",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_port.c:554",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898976,
      "name": "serial8250_clear_fifos.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void serial8250_clear_fifos(struct uart_8250_port * p)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void serial8250_clear_fifos(struct uart_8250_port * p)
```
</details>
</li>
</ul>
