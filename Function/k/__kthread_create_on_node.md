# Function: <code>__kthread_create_on_node</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535968,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:265",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535968,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523136,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:269",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523136,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549520,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:276",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549520,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578816,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:284",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578816,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616000,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:284",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616000,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638448,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638448,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664384,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664384,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700224,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:329",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700224,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678384,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:330",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678384,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684656,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:357",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684656,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762944,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:357",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762944,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868416,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:414",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868416,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011088,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:414",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011088,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064736,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:429",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064736,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107296,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:428",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107296,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490842992,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490842992,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224874784,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224874784,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283677056,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283677056,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271513034,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271513034,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640704,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640704,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569104,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569104,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637968,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637968,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_on_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671808,
      "name": "__kthread_create_on_node",
      "external": false,
      "loc": "kernel/kthread.c:293",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671808,
      "name": "__kthread_create_on_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct task_struct * __kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, struct __va_list_tag * args)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
