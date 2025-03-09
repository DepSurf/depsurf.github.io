# Function: <code>vc_cons_allocated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584051949,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:738",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:con_font_op"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:update_user_maps",
        "drivers/tty/vt/consolemap.c:console_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063760,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584406082,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:732",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394544,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584588482,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:721",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576864,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584669908,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:729",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658528,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585082258,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:731",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070848,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585316821,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:731",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305584,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585440005,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1036",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427584,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585655798,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1036",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585642176,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585797139,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783472,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586528037,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1054",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:setterm_command",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516192,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586633060,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1060",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:setterm_command",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629392,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586517204,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1059",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513568,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052669,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048672,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588355350,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350384,
      "name": "vc_cons_allocated",
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589776518,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771344,
      "name": "vc_cons_allocated",
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590081430,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:998",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590076272,
      "name": "vc_cons_allocated",
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590420630,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:997",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:set_console",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590415408,
      "name": "vc_cons_allocated",
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498516024,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498501104,
      "name": "vc_cons_allocated",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231168232,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231155260,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291713932,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:do_unblank_screen",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291694912,
      "name": "vc_cons_allocated",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276142426,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:con_unify_unimap",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276131240,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585558131,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544464,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585427955,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414288,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747539,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585733872,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vc_cons_allocated(unsigned int i)
```

```json
{
  "name": "vc_cons_allocated",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585855523,
      "name": "vc_cons_allocated",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:1048",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:con_start",
        "drivers/tty/vt/vt.c:con_stop",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/vt/vt.c:console_callback",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:vc_deallocate"
      ],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_open",
        "drivers/tty/vt/keyboard.c:fn_inc_console",
        "drivers/tty/vt/keyboard.c:fn_dec_console",
        "drivers/tty/vt/consolemap.c:console_map_init",
        "drivers/tty/vt/consolemap.c:update_user_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841888,
      "name": "vc_cons_allocated",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
