# Function: <code>alarm_setitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830240,
      "name": "alarm_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:253",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:SyS_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830240,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858960,
      "name": "alarm_setitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:253",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:SyS_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858960,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579934422,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:255",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:SyS_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579942254,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:255",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:SyS_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579987902,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:256",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:SyS_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039456,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:256",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039456,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086256,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:255",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086256,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129888,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:255",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129888,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178144,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178144,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580241212,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:281",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580225452,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580230625,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580379569,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580597825,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580860657,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944417,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035713,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:277",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284345452,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__se_sys_alarm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147344,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147344,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092848,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092848,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138416,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138416,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int alarm_setitimer(unsigned int seconds)
```

```json
{
  "name": "alarm_setitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190352,
      "name": "alarm_setitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:251",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_alarm",
        "kernel/time/itimer.c:__x64_sys_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190352,
      "name": "alarm_setitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds)
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
