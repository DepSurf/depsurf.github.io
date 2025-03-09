# Function: <code>__kthread_create_worker</code>

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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539120,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:652",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539120,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526000,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:658",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526000,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552160,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:665",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552160,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579376,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:683",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579376,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616560,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:685",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616560,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640912,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640912,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667344,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667344,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700768,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:730",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700768,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678928,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:763",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678928,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685200,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:790",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685200,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763488,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:790",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763488,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869280,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:850",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869280,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012000,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:851",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012000,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065536,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:852",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065536,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108144,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:869",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108144,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490844648,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490844648,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224875384,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224875384,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283681280,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283681280,
      "name": "__kthread_create_worker",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, va_list args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271513548,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271513548,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643664,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643664,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572048,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572048,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640928,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640928,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
```

```json
{
  "name": "__kthread_create_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675168,
      "name": "__kthread_create_worker",
      "external": false,
      "loc": "kernel/kthread.c:694",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_worker_on_cpu",
        "kernel/kthread.c:kthread_create_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675168,
      "name": "__kthread_create_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct kthread_worker * __kthread_create_worker(int cpu, unsigned int flags, const char * namefmt, struct __va_list_tag * args)
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
