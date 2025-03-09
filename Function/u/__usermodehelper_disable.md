# Function: <code>__usermodehelper_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462704,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/kmod.c:457",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_power_off",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462704,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475952,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/kmod.c:457",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475952,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496352,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/kmod.c:457",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496352,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486128,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/kmod.c:474",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486128,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512896,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:305",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512896,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539920,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:312",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539920,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576592,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:316",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576592,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600032,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600032,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625888,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625888,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655168,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655168,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635328,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:294",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635328,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641984,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:296",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641984,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718592,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:296",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718592,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820576,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:296",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820576,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957040,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:297",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957040,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007376,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:294",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007376,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047088,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:294",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047088,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490791832,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490791832,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224828088,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224828088,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283618080,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283618080,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271473064,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271473064,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602192,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602192,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530832,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530832,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599472,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599472,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __usermodehelper_disable(enum umh_disable_depth depth)
```

```json
{
  "name": "__usermodehelper_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633104,
      "name": "__usermodehelper_disable",
      "external": true,
      "loc": "kernel/umh.c:317",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart_prepare",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633104,
      "name": "__usermodehelper_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
