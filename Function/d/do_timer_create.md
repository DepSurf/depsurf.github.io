# Function: <code>do_timer_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926144,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:493",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926144,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971632,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:499",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "kernel/time/posix-timers.c:compat_SyS_timer_create",
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971632,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1139
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022656,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:508",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022656,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069712,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069712,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114896,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114896,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164208,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164208,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223952,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223952,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208208,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208208,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217424,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217424,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1310
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365312,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x64_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365312,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575008,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575008,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836032,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:498",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836032,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919552,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:444",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919552,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010160,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:444",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010160,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491385216,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__arm64_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__arm64_sys_timer_create",
        "kernel/time/posix-timers.c:__arm64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491385216,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225380136,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225380136,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284325744,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__se_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__se_sys_timer_create",
        "kernel/time/posix-timers.c:__se_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284325744,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1604
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271868122,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_create",
        "kernel/time/posix-timers.c:__se_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271868122,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133408,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133408,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078704,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078704,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1173
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124480,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124480,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```

```json
{
  "name": "do_timer_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176624,
      "name": "do_timer_create",
      "external": false,
      "loc": "kernel/time/posix-timers.c:472",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__ia32_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create",
        "kernel/time/posix-timers.c:__x64_sys_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176624,
      "name": "do_timer_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent * event, timer_t * created_timer_id)
```
</details>
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
