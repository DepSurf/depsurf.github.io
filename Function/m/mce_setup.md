# Function: <code>mce_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127520,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:126",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127520,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127648,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:125",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127648,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134736,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:127",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134736,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579133456,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:116",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133456,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148336,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:123",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148336,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158240,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:118",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158240,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147728,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:116",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147728,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160352,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160352,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579162816,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579162816,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591158288,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591158288,
      "name": "mce_setup",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591652176,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591652176,
      "name": "mce_setup",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591596032,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596032,
      "name": "mce_setup",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592769424,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592769424,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273296,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:124",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273296,
      "name": "mce_setup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337488,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:124",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337488,
      "name": "mce_setup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346368,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:118",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346368,
      "name": "mce_setup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376368,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:120",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376368,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163168,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163168,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094720,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094720,
      "name": "mce_setup",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579162736,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579162736,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```

```json
{
  "name": "mce_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167920,
      "name": "mce_setup",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:133",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167920,
      "name": "mce_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mce_setup(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mce_setup(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mce_setup(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mce_setup(struct mce * m)
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
