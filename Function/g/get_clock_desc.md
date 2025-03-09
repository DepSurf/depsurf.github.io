# Function: <code>get_clock_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869696,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:249",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_timer_gettime",
        "kernel/time/posix-clock.c:pc_timer_delete",
        "kernel/time/posix-clock.c:pc_timer_settime",
        "kernel/time/posix-clock.c:pc_timer_create",
        "kernel/time/posix-clock.c:pc_clock_adjtime",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869696,
      "name": "get_clock_desc",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899040,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:249",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_timer_settime",
        "kernel/time/posix-clock.c:pc_timer_gettime",
        "kernel/time/posix-clock.c:pc_timer_delete",
        "kernel/time/posix-clock.c:pc_timer_create",
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899040,
      "name": "get_clock_desc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930976,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:249",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_timer_settime",
        "kernel/time/posix-clock.c:pc_timer_gettime",
        "kernel/time/posix-clock.c:pc_timer_delete",
        "kernel/time/posix-clock.c:pc_timer_create",
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930976,
      "name": "get_clock_desc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939424,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:217",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939424,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984800,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:217",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984800,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036176,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:217",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036176,
      "name": "get_clock_desc.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082992,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:204",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082992,
      "name": "get_clock_desc.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126688,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:204",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126688,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580175104,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175104,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238304,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238304,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222560,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222560,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227728,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227728,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376272,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071592156561,
      "name": "get_clock_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580593376,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071593931581,
      "name": "get_clock_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855936,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071595998131,
      "name": "get_clock_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939728,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071596516277,
      "name": "get_clock_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:217",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030992,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071597415727,
      "name": "get_clock_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491397480,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491397480,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225395328,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225395328,
      "name": "get_clock_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284341008,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284341008,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271878410,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271878410,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144304,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144304,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580089856,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089856,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580135376,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135376,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_clock_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580187264,
      "name": "get_clock_desc",
      "external": false,
      "loc": "kernel/time/posix-clock.c:199",
      "file": "kernel/time/posix-clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:pc_clock_settime",
        "kernel/time/posix-clock.c:pc_clock_getres",
        "kernel/time/posix-clock.c:pc_clock_gettime",
        "kernel/time/posix-clock.c:pc_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187264,
      "name": "get_clock_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc * cd)
```
</details>
</li>
</ul>
