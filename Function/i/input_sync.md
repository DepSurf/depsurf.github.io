# Function: <code>input_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void input_sync(struct input_dev * dev)
```

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739606,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/acpi/button.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_lid_send_state",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ]
    },
    {
      "addr": 18446744071585597060,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739606,
      "name": "input_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void input_sync(struct input_dev * dev)
```

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584063776,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/acpi/button.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ]
    },
    {
      "addr": 18446744071585991093,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063776,
      "name": "input_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void input_sync(struct input_dev * dev)
```

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584205987,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/acpi/button.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ]
    },
    {
      "addr": 18446744071586179221,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586190878,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:412",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205987,
      "name": "input_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584275000,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:417",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266160,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:417",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586278994,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:417",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584672072,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586729587,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586742306,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584898283,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586995984,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008694,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585002155,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157216,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587170134,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:421",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585205774,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:418",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587422235,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:418",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587433148,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:418",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585342142,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587625291,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587636204,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586050708,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:440",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493409,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:440",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588498837,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:440",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586173684,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588522673,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588527621,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586050185,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588404144,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410249,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586542162,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589073112,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589077299,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587800053,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590509459,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590520009,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589138019,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592156613,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592167913,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589427683,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592580107,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592591418,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589738922,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593324843,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593336202,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:448",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497629332,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500780068,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233291540,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3234379652,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "sound/core/jack.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294232992,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277609806,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585146681,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587318107,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585061865,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086475,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293726,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576539,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587587452,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "input_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585399886,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587688107,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587698348,
      "name": "input_sync",
      "external": false,
      "loc": "include/linux/input.h:439",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void input_sync(struct input_dev * dev)
```
</details>
</li>
</ul>
