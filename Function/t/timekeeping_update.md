# Function: <code>timekeeping_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847648,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:579",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847648,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876768,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:584",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876768,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888800,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:613",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888800,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897712,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:644",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897712,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942288,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:647",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942288,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990336,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:648",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990336,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036960,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:655",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036960,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079936,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079936,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128944,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128944,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190928,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190928,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175680,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:738",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175680,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179504,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:738",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179504,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:738",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324736,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071592152010,
      "name": "timekeeping_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:757",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536800,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071593927010,
      "name": "timekeeping_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:757",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793488,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071595995055,
      "name": "timekeeping_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:757",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876752,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071596513383,
      "name": "timekeeping_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:757",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967184,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071597412710,
      "name": "timekeeping_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491349096,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491349096,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225343296,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225343296,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284280656,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284280656,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271843474,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271843474,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098144,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098144,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043456,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043456,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089216,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089216,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void timekeeping_update(struct timekeeper * tk, unsigned int action)
```

```json
{
  "name": "timekeeping_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140960,
      "name": "timekeeping_update",
      "external": false,
      "loc": "kernel/time/timekeeping.c:661",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140960,
      "name": "timekeeping_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
