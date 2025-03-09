# Function: <code>sem_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582150480,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:381",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:newary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150480,
      "name": "sem_unlock.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582378175,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:377",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366272,
      "name": "sem_unlock.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470283,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:399",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459472,
      "name": "sem_unlock.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582550955,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:399",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539616,
      "name": "sem_unlock.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582701702,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:401",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689392,
      "name": "sem_unlock.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582896881,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:439",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884032,
      "name": "sem_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005009,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992144,
      "name": "sem_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583186548,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583292362,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583623024,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:457",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583743660,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:457",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583768016,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:457",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584129934,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:460",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584727299,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:460",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585420547,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:460",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585651188,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:460",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585897916,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:460",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495028772,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228434200,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228419292,
      "name": "sem_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288913788,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274309516,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
      ],
      "caller_func": [
        "ipc/sem.c:__se_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274300016,
      "name": "sem_unlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583261098,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583198250,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583245130,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sem_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583339540,
      "name": "sem_unlock",
      "external": false,
      "loc": "ipc/sem.c:438",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:newary",
        "ipc/sem.c:newary"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sem_unlock(struct sem_array * sma, int locknum)
```
</details>
</li>
</ul>
