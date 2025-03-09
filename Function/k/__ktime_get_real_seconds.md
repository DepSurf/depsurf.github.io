# Function: <code>__ktime_get_real_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851360,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:871",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851360,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880576,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:876",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880576,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892384,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:905",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892384,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:937",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901232,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:941",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946032,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994016,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:942",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994016,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041968,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:949",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041968,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085312,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085312,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134400,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134400,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164592,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164592,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591660144,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1025",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591660144,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603824,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1025",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603824,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776704,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1025",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776704,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594674352,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1044",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594674352,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408592,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1044",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408592,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596940624,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1044",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596940624,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597867216,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1044",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/time/ntp.c:ntp_update_offset",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597867216,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491355368,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491355368,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225353196,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225353196,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284287808,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284287808,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271848166,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271848166,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103600,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103600,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048912,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048912,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094672,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094672,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
time64_t __ktime_get_real_seconds()
```

```json
{
  "name": "__ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146416,
      "name": "__ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:956",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146416,
      "name": "__ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
