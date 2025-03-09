# Function: <code>input_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585570720,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:429",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:input_sync",
        "drivers/acpi/button.c:acpi_lid_send_state",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585570720,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585964640,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:input_sync",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964640,
      "name": "input_event",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153024,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:input_sync",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153024,
      "name": "input_event",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586241872,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241872,
      "name": "input_event",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586705296,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705296,
      "name": "input_event",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586971536,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971536,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587132576,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:428",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132576,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587397376,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:424",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397376,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587599504,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587599504,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460784,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_inject_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460784,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588491296,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:438",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_inject_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588491296,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588369744,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:438",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369744,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589033824,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:438",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589033824,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590475296,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:449",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590475296,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592122448,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:424",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122448,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592545824,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:427",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592545824,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593290272,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:427",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/input-mt.c:input_mt_report_slot_state",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen.c:touchscreen_report_pos",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593290272,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500744048,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500744048,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233264252,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233264252,
      "name": "input_event",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294194064,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294194064,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277586174,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277586174,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587292320,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292320,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587060720,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060720,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587550752,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587550752,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void input_event(struct input_dev * dev, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587661808,
      "name": "input_event",
      "external": true,
      "loc": "drivers/input/input.c:433",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:__input_mt_drop_unused",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_pointer_emulation",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/input-mt.c:input_mt_report_finger_count",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_event",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587661808,
      "name": "input_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
