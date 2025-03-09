# Function: <code>__tty_check_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583957344,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_io.c:393",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/n_tty.c:n_tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957344,
      "name": "__tty_check_change.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071583964432,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584299891,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_io.c:396",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/n_tty.c:n_tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291216,
      "name": "__tty_check_change.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071584296896,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584481955,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_io.c:396",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/n_tty.c:n_tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473296,
      "name": "__tty_check_change.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071584478960,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602030,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:30",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599728,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071584600064,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585014483,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011680,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071585012512,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248704,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245840,
      "name": "__tty_check_change.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071585246688,
      "name": "__tty_check_change",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368268,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365248,
      "name": "__tty_check_change.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071585366096,
      "name": "__tty_check_change",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585581918,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578928,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585579840,
      "name": "__tty_check_change",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585722830,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719840,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585720752,
      "name": "__tty_check_change",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586450805,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tiocspgrp"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tiocspgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449616,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071586451264,
      "name": "__tty_check_change",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586564096,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:32",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564096,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071586565744,
      "name": "__tty_check_change",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586452605,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449040,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071586450224,
      "name": "__tty_check_change",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586979549,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975936,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071592447148,
      "name": "__tty_check_change.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586977168,
      "name": "__tty_check_change",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588276569,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272720,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071594315208,
      "name": "__tty_check_change.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071588274032,
      "name": "__tty_check_change",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589691801,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687744,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071596233355,
      "name": "__tty_check_change.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071589689136,
      "name": "__tty_check_change",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589996470,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589992352,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071596761277,
      "name": "__tty_check_change.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589993776,
      "name": "__tty_check_change",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590334870,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:33",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590330880,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071597669837,
      "name": "__tty_check_change.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590332304,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498416884,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498412880,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446603336498413752,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231087480,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231084736,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 3231085128,
      "name": "__tty_check_change",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291600468,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291597632,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 13835058055291598112,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276072688,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276070328,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446743936276070630,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483854,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480864,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585481776,
      "name": "__tty_check_change",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585353752,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350784,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585351696,
      "name": "__tty_check_change",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585673230,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670240,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585671152,
      "name": "__tty_check_change",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tty_check_change(struct tty_struct * tty, int sig)
```

```json
{
  "name": "__tty_check_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585781313,
      "name": "__tty_check_change",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:31",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778336,
      "name": "__tty_check_change.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071585779280,
      "name": "__tty_check_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
