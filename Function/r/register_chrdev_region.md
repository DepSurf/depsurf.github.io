# Function: <code>register_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011280,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:174",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/usb/core/devio.c:usb_devio_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011280,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169776,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:178",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169776,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246752,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:178",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246752,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294800,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:178",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294800,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434592,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:203",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434592,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592160,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:203",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592160,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677424,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:203",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677424,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795456,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795456,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868064,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868064,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094352,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094352,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141168,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141168,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166032,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166032,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483232,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483232,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004240,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004240,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566240,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566240,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782336,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782336,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987920,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:unix98_pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987920,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493340320,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493340320,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226933860,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226933860,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286886160,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286886160,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273070210,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070210,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836800,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836800,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774464,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774464,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828112,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828112,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int register_chrdev_region(dev_t from, unsigned int count, const char * name)
```

```json
{
  "name": "register_chrdev_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897392,
      "name": "register_chrdev_region",
      "external": true,
      "loc": "fs/char_dev.c:200",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/tty/pty.c:pty_init",
        "drivers/tty/vt/vt.c:vty_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/usb/core/devio.c:usb_devio_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897392,
      "name": "register_chrdev_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
