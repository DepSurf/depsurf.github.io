# Function: <code>perform_atomic_semop_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582457936,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:584",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582536654,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:595",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582686286,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:598",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:630",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:629",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605488,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:644",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605488,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725728,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:643",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725728,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750112,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:643",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750112,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111808,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:646",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111808,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709456,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:646",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709456,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585402160,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:646",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585402160,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632960,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:646",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:perform_atomic_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632960,
      "name": "perform_atomic_semop_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585880323,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:646",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228420616,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274297370,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
  "name": "perform_atomic_semop_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perform_atomic_semop_slow",
      "external": false,
      "loc": "ipc/sem.c:625",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:perform_atomic_semop"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int perform_atomic_semop_slow(struct sem_array * sma, struct sem_queue * q)
```
</details>
</li>
</ul>
