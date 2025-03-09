# Function: <code>exit_oom_victim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486256,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:437",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486256,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void exit_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569456,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:688",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569456,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637552,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:678",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637552,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669616,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:681",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669616,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754672,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:705",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754672,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889664,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:707",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889664,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963376,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:715",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963376,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060400,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060400,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116176,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116176,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581300000,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:727",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300000,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344000,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:729",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344000,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363088,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:728",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363088,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610896,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:729",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610896,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971104,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:786",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971104,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405264,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:785",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405264,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611280,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:785",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611280,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782848,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:782",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782848,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492484560,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492484560,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226357684,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226357684,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285770752,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285770752,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272549162,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272549162,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085024,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085024,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032208,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032208,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076224,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076224,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void exit_oom_victim()
```

```json
{
  "name": "exit_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138080,
      "name": "exit_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:725",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138080,
      "name": "exit_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
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
