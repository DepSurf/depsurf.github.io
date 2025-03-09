# Function: <code>__cgroup_bpf_run_filter_setsockopt</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909376,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:977",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909376,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963248,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963248,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132896,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1303",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132896,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 714
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167056,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1327",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167056,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184352,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1350",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184352,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1080
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424784,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1380",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424784,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751088,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1548",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751088,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166160,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1787",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166160,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1787",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544930,
      "name": "__cgroup_bpf_run_filter_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582363088,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, sockptr_t optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1802",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597448625,
      "name": "__cgroup_bpf_run_filter_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582529984,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 975
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492313640,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492313640,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226198864,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226198864,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285552784,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285552784,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272440844,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272440844,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932048,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932048,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878112,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878112,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923296,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923296,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983600,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:986",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983600,
      "name": "__cgroup_bpf_run_filter_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock * sk, int * level, int * optname, char * optval, int * optlen, char * * kernel_optval)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
