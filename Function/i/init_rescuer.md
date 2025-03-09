# Function: <code>init_rescuer</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565879,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4020",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544272,
      "name": "init_rescuer.part.29",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603111,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4043",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581024,
      "name": "init_rescuer.part.30",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626483,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4183",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605024,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579652595,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630560,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660304,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4210",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660304,
      "name": "init_rescuer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640032,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4223",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640032,
      "name": "init_rescuer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646480,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4230",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646480,
      "name": "init_rescuer",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579723184,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4269",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723184,
      "name": "init_rescuer",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828032,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4252",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828032,
      "name": "init_rescuer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965680,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4261",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965680,
      "name": "init_rescuer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015776,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4589",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015776,
      "name": "init_rescuer",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
```

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055760,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4629",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055760,
      "name": "init_rescuer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490825424,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490796776,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224858536,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224835540,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283660440,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283629344,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271498646,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271477438,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628899,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606864,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557251,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535504,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626179,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604144,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "init_rescuer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659827,
      "name": "init_rescuer",
      "external": false,
      "loc": "kernel/workqueue.c:4201",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:workqueue_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639760,
      "name": "init_rescuer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int init_rescuer(struct workqueue_struct * wq)
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
