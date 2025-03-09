# Function: <code>ipc_rcu_putref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ipc_rcu_putref(void * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141552,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:456",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:newque",
        "ipc/msg.c:newque",
        "ipc/msg.c:freeque",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141552,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ipc_rcu_putref(void * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357600,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:451",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/msg.c:newque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357600,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void ipc_rcu_putref(void * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448960,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:451",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/msg.c:newque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448960,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527952,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:403",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527952,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582676320,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:466",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676320,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582869760,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:470",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582869760,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977936,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:470",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977936,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158832,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158832,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264896,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583264896,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583592880,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592880,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713232,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713232,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737744,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737744,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099408,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:533",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099408,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584694832,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:533",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694832,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386032,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:533",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386032,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616704,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:533",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616704,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585863424,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:533",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863424,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494995448,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494995448,
      "name": "ipc_rcu_putref",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228408868,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228408868,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288875664,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288875664,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274288776,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274288776,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233632,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233632,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170784,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170784,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217664,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217664,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void ipc_rcu_putref(struct kern_ipc_perm * ptr, void (*)(struct callback_head *) func)
```

```json
{
  "name": "ipc_rcu_putref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311888,
      "name": "ipc_rcu_putref",
      "external": true,
      "loc": "ipc/util.c:499",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:newque",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311888,
      "name": "ipc_rcu_putref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * ptr</code> ➡️ <code>struct kern_ipc_perm * ptr</code>
</li>
</ul>
</details>
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
