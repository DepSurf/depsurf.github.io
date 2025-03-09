# Function: <code>core_sys_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079600,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:547",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_select",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079600,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242544,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:551",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242544,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320368,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:552",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320368,
      "name": "core_sys_select",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375792,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:599",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375792,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517264,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:598",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517264,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678304,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:594",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_pselect",
        "fs/select.c:do_pselect",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678304,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764896,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:619",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764896,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882240,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__do_sys_pselect6",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882240,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954464,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954464,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186688,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186688,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234128,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234128,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259904,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259904,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577792,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:624",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577792,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583106528,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:625",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106528,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675056,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:625",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675056,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892320,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:625",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892320,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1518
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099488,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:625",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099488,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1514
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493450544,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493450544,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227017048,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_pselect",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227017048,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1232
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287005344,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287005344,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273134826,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273134826,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923200,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923200,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860784,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860784,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914512,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914512,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int core_sys_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec64 * end_time)
```

```json
{
  "name": "core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984144,
      "name": "core_sys_select",
      "external": true,
      "loc": "fs/select.c:621",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984144,
      "name": "core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * end_time</code> ➡️ <code>struct timespec64 * end_time</code>
</li>
</ul>
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
