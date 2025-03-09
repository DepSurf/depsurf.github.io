# Function: <code>do_poweroff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723088,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583856112,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723088,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071583856112,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743184,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584185984,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743184,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584185984,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770528,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584366960,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:189",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770528,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584366960,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766752,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584448496,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:189",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766752,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584448496,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800240,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584858480,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:186",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800240,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584858480,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833824,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585089104,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:186",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833824,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585089104,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880560,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:20",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585199280,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:186",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880560,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585199280,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915104,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915104,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585411760,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585412780,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965152,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965152,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585552464,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585553484,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010416,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010416,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071586270992,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586272173,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988240,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988240,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071586388736,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071591448115,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990080,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990080,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071586272752,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071591389885,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122016,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122016,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071586784768,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071592433399,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580262896,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594301547,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262896,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588065472,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071594301547,
      "name": "do_poweroff.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468448,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589446432,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468448,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589446432,
      "name": "do_poweroff",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539904,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589745856,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539904,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589745856,
      "name": "do_poweroff",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601712,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590083872,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:188",
      "file": "drivers/xen/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601712,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590083872,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491146128,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498213840,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491146128,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336498213840,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225175312,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225175312,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284040608,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284040608,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271703644,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271703644,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933888,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:221",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933888,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585313776,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585314981,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872160,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872160,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925424,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925424,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585502864,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585503884,
      "name": "do_poweroff.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_poweroff(struct work_struct * dummy)
```

```json
{
  "name": "do_poweroff",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971424,
      "name": "do_poweroff",
      "external": false,
      "loc": "kernel/power/poweroff.c:19",
      "file": "kernel/power/poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_poweroff",
      "external": false,
      "loc": "drivers/xen/manage.c:187",
      "file": "drivers/xen/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971424,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585610896,
      "name": "do_poweroff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585611916,
      "name": "do_poweroff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
