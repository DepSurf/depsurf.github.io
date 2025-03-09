# Function: <code>timers_update_migration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz)
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821248,
      "name": "timers_update_migration",
      "external": true,
      "loc": "kernel/time/timer.c:103",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821248,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void timers_update_migration(bool update_nohz)
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849888,
      "name": "timers_update_migration",
      "external": true,
      "loc": "kernel/time/timer.c:213",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849888,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void timers_update_migration(bool update_nohz)
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878672,
      "name": "timers_update_migration",
      "external": true,
      "loc": "kernel/time/timer.c:213",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878672,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void timers_update_migration(bool update_nohz)
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888048,
      "name": "timers_update_migration",
      "external": true,
      "loc": "kernel/time/timer.c:216",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888048,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void timers_update_migration(bool update_nohz)
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932320,
      "name": "timers_update_migration",
      "external": true,
      "loc": "kernel/time/timer.c:216",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932320,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970944,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:224",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970944,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018016,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:223",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018016,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062192,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:223",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062192,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111248,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111248,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580178756,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:228",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580163876,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:229",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168420,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:230",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580313204,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:230",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580518709,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:231",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_migration_handler"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580773269,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:231",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_migration_handler"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856661,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:231",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_migration_handler"
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
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946821,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:231",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_migration_handler"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491322464,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491322464,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225320264,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225320264,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284252768,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284252768,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271827640,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271827640,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080448,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080448,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025264,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025264,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071520,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071520,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void timers_update_migration()
```

```json
{
  "name": "timers_update_migration",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121712,
      "name": "timers_update_migration",
      "external": false,
      "loc": "kernel/time/timer.c:227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121712,
      "name": "timers_update_migration",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<b>Param removed. </b>
<code>bool update_nohz</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void timers_update_migration()
```
</details>
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
