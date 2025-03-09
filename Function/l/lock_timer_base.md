# Function: <code>lock_timer_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812912,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:762",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812912,
      "name": "lock_timer_base.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579843280,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:940",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843280,
      "name": "lock_timer_base.isra.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867680,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:934",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867680,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877200,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:906",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877200,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920448,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:913",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920448,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966912,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:921",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966912,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013776,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:920",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013776,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057632,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:915",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057632,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106688,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106688,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167808,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:930",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167808,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153072,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:927",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153072,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157680,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:929",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157680,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580302208,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:929",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302208,
      "name": "lock_timer_base",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511360,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:982",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:del_timer_sync",
        "kernel/time/timer.c:del_timer",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511360,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765600,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:982",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765600,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848528,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:982",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848528,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938000,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:982",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:timer_shutdown",
        "kernel/time/timer.c:timer_delete",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938000,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491323016,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491323016,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225314020,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225314020,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284245920,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:add_timer",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284245920,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271823142,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271823142,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075888,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075888,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020704,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020704,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066960,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066960,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```

```json
{
  "name": "lock_timer_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117728,
      "name": "lock_timer_base",
      "external": false,
      "loc": "kernel/time/timer.c:919",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:try_to_del_timer_sync",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117728,
      "name": "lock_timer_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct timer_base * lock_timer_base(struct timer_list * timer, long unsigned int * flags)
```
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
