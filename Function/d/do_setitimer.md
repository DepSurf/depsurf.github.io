# Function: <code>do_setitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829680,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:alarm_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/compat.c:compat_SyS_setitimer",
        "kernel/compat.c:compat_SyS_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829680,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858400,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "kernel/compat.c:compat_SyS_setitimer",
        "kernel/compat.c:compat_SyS_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858400,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933856,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_alarm",
        "kernel/compat.c:compat_SyS_setitimer",
        "kernel/compat.c:compat_SyS_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933856,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941664,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_alarm",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941664,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987312,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:191",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_setitimer",
        "kernel/time/itimer.c:SyS_alarm",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987312,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038864,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:191",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038864,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085664,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085664,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129328,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:190",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129328,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177584,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177584,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240640,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:210",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240640,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224896,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224896,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230064,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230064,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379008,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x64_compat_sys_setitimer",
        "kernel/time/itimer.c:__x64_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379008,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597232,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597232,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860048,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860048,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943808,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943808,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int do_setitimer(int which, struct itimerspec64 * value, struct itimerspec64 * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035104,
      "name": "do_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:206",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer",
        "kernel/time/itimer.c:clear_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035104,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491400496,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__arm64_compat_sys_setitimer",
        "kernel/time/itimer.c:__arm64_compat_sys_setitimer",
        "kernel/time/itimer.c:__arm64_sys_setitimer",
        "kernel/time/itimer.c:__arm64_sys_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491400496,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225397812,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_sys_setitimer",
        "kernel/time/itimer.c:__se_sys_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225397812,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284344448,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_compat_sys_setitimer",
        "kernel/time/itimer.c:__se_compat_sys_setitimer",
        "kernel/time/itimer.c:__se_sys_setitimer",
        "kernel/time/itimer.c:__se_sys_setitimer",
        "kernel/time/itimer.c:__se_sys_alarm",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284344448,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271880292,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_sys_setitimer",
        "kernel/time/itimer.c:__se_sys_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271880292,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146784,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146784,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092304,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092304,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137856,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137856,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int do_setitimer(int which, struct itimerval * value, struct itimerval * ovalue)
```

```json
{
  "name": "do_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189776,
      "name": "do_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:185",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer",
        "kernel/time/itimer.c:alarm_setitimer",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189776,
      "name": "do_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct itimerval * value</code> ➡️ <code>struct itimerspec64 * value</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerval * ovalue</code> ➡️ <code>struct itimerspec64 * ovalue</code>
</li>
</ul>
</details>
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
