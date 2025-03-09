# Function: <code>tboot_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099424,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:222",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099424,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098944,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:216",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098944,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097072,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:216",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097072,
      "name": "tboot_shutdown",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088976,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:220",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088976,
      "name": "tboot_shutdown",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099760,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:231",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099760,
      "name": "tboot_shutdown",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:231",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106201,
      "name": "tboot_shutdown.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579105280,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110955,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:231",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111833,
      "name": "tboot_shutdown.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579110912,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579120923,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121793,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579120880,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579122795,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123665,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579122752,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137504,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:220",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137504,
      "name": "tboot_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071579138016,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135504,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:221",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135504,
      "name": "tboot_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071579136016,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142085,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:229",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195218,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579142032,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579169038,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:229",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061002,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579168976,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579214718,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:228",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593827532,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579214656,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271408,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:227",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271408,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277680,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:227",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277680,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306816,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:227",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_sleep",
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306816,
      "name": "tboot_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579307680,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579123179,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124049,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579123136,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579055131,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055985,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579055088,
      "name": "tboot_shutdown",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579122731,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123601,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579122688,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void tboot_shutdown(u32 shutdown_type)
```

```json
{
  "name": "tboot_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127851,
      "name": "tboot_shutdown",
      "external": true,
      "loc": "arch/x86/kernel/tboot.c:218",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "arch/x86/kernel/reboot.c:native_machine_halt",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128721,
      "name": "tboot_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579127808,
      "name": "tboot_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tboot_shutdown(u32 shutdown_type)
```
</details>
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
