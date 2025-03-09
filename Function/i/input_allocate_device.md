# Function: <code>input_allocate_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567344,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1782",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567344,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585960464,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1781",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960464,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586148848,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1781",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586148848,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237680,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1781",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_allocate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237680,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701104,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1775",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701104,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586967632,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1783",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967632,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128496,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1783",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128496,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587392352,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1779",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392352,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587594384,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594384,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588452464,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1810",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452464,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588482672,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1908",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482672,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364256,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1908",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364256,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589028096,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1908",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589028096,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590467248,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1953",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590467248,
      "name": "input_allocate_device",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592110880,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1937",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592110880,
      "name": "input_allocate_device",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592534624,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1936",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592534624,
      "name": "input_allocate_device",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593279104,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1936",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593279104,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500738360,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500738360,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233252380,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler",
        "drivers/input/misc/uinput.c:uinput_write",
        "sound/core/jack.c:snd_jack_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233252380,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294185920,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294185920,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277579946,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_ioctl_handler",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277579946,
      "name": "input_allocate_device",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587287200,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587287200,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055632,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055632,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587545632,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587545632,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct input_dev * input_allocate_device()
```

```json
{
  "name": "input_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587656832,
      "name": "input_allocate_device",
      "external": true,
      "loc": "drivers/input/input.c:1812",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656832,
      "name": "input_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
