# Function: <code>detach_if_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list * timer, struct tvec_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810256,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:733",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810256,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838416,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:831",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838416,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867472,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:831",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867472,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876992,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:797",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876992,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920240,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:806",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920240,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971824,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:823",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971824,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013568,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:822",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013568,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057792,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:817",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057792,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106848,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106848,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172768,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:829",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172768,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157840,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:831",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157840,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162320,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:833",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162320,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307024,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:833",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307024,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518944,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:886",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518944,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773840,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:886",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773840,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856928,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:886",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856928,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947088,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:883",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947088,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491330224,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491330224,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225318500,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225318500,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284245520,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284245520,
      "name": "detach_if_pending",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271826208,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271826208,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076048,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076048,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020864,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020864,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067120,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067120,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int detach_if_pending(struct timer_list * timer, struct timer_base * base, bool clear_pending)
```

```json
{
  "name": "detach_if_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121840,
      "name": "detach_if_pending",
      "external": false,
      "loc": "kernel/time/timer.c:821",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121840,
      "name": "detach_if_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
<b>Param type changed. </b>
<code>struct tvec_base * base</code> ➡️ <code>struct timer_base * base</code>
</li>
</ul>
</details>
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
