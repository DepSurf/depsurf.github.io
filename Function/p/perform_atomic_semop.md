# Function: <code>perform_atomic_semop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582150592,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:613",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:wake_const_ops",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150592,
      "name": "perform_atomic_semop.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582366384,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:609",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366384,
      "name": "perform_atomic_semop.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457904,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:655",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457904,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536320,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:666",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536320,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685952,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:669",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685952,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881552,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:703",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881552,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990160,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:702",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990160,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171104,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171104,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583277088,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277088,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605968,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:717",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605968,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726208,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:716",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726208,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750592,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:716",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750592,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:719",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112288,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071592291015,
      "name": "perform_atomic_semop.cold",
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:719",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709952,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071594073145,
      "name": "perform_atomic_semop.cold",
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:719",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585402672,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071596092850,
      "name": "perform_atomic_semop.cold",
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:719",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585633472,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071596616199,
      "name": "perform_atomic_semop.cold",
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:719",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879728,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
    },
    {
      "addr": 18446744071597522103,
      "name": "perform_atomic_semop.cold",
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495011544,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495011544,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228420244,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228420244,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288894192,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288894192,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274297140,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274297140,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245824,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245824,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182976,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182976,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229856,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229856,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324816,
      "name": "perform_atomic_semop",
      "external": false,
      "loc": "ipc/sem.c:698",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324816,
      "name": "perform_atomic_semop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int perform_atomic_semop(struct sem_array * sma, struct sem_queue * q)
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
