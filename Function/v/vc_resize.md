# Function: <code>vc_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059152,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:981",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_startup",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059152,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388496,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:980",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388496,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571328,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:974",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571328,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652880,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:982",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/console/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/console/fbcon.c:fbcon_modechanged",
        "drivers/video/console/fbcon.c:fbcon_do_set_font",
        "drivers/video/console/fbcon.c:fbcon_set_disp",
        "drivers/video/console/fbcon.c:fbcon_init",
        "drivers/video/console/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652880,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068448,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068448,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303744,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:984",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303744,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585425088,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1305",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585425088,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585639632,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1313",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639632,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585780928,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780928,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586511872,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1350",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511872,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626800,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1355",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626800,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586507776,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1354",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507776,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039904,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1360",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039904,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588342176,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1360",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342176,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589763216,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1360",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589763216,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068080,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1310",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068080,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590407248,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1309",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_adjust_height",
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_resizex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590407248,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498498640,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498498640,
      "name": "vc_resize",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231152784,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231152784,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291691360,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291691360,
      "name": "vc_resize",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276129080,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276129080,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541920,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541920,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411744,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411744,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731328,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731328,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vc_resize(struct vc_data * vc, unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585839344,
      "name": "vc_resize",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1337",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/vgacon.c:vgacon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs",
        "drivers/video/fbdev/core/fbcon.c:fbcon_modechanged",
        "drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font",
        "drivers/video/fbdev/core/fbcon.c:fbcon_set_disp",
        "drivers/video/fbdev/core/fbcon.c:fbcon_init",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585839344,
      "name": "vc_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
