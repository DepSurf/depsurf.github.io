# Function: <code>do_sigaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440576,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3047",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:SyS_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440576,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453232,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3047",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_signal",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453232,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473712,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3065",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_signal",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473712,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461504,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_signal",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461504,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489552,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3141",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_signal",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:C_SYSC_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction",
        "kernel/signal.c:SyS_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489552,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509328,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3374",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509328,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545008,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3698",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545008,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566768,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3946",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566768,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592896,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592896,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625744,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3972",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625744,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606032,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3993",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606032,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612160,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4015",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612160,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688208,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4103",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x64_compat_sys_sigaction",
        "kernel/signal.c:__x64_compat_sys_sigaction",
        "kernel/signal.c:__x64_compat_sys_sigaction",
        "kernel/signal.c:__x64_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688208,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786960,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4086",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786960,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921104,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4088",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921104,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971008,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4112",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971008,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010416,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:4123",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010416,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490756616,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__arm64_sys_rt_sigaction",
        "kernel/signal.c:__arm64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490756616,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224804224,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_sys_sigaction",
        "kernel/signal.c:__do_sys_sigaction",
        "kernel/signal.c:__se_sys_rt_sigaction",
        "kernel/signal.c:__se_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224804224,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283582128,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_signal",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__se_compat_sys_rt_sigaction",
        "kernel/signal.c:__se_compat_sys_rt_sigaction",
        "kernel/signal.c:__se_sys_rt_sigaction",
        "kernel/signal.c:__se_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283582128,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271456828,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigaction",
        "kernel/signal.c:__se_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271456828,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569200,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569200,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497808,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497808,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566480,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566480,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
int do_sigaction(int sig, struct k_sigaction * act, struct k_sigaction * oact)
```

```json
{
  "name": "do_sigaction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599968,
      "name": "do_sigaction",
      "external": true,
      "loc": "kernel/signal.c:3954",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_signal",
        "kernel/signal.c:__x64_sys_signal",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__ia32_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction",
        "kernel/signal.c:__x64_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599968,
      "name": "do_sigaction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
