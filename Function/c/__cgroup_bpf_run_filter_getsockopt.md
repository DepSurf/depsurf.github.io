# Function: <code>__cgroup_bpf_run_filter_getsockopt</code>

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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910048,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1040",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910048,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962448,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962448,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581133616,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1379",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133616,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167824,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1404",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167824,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185440,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1444",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185440,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425712,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1474",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425712,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751952,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1632",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751952,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167040,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1871",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167040,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1877",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544951,
      "name": "__cgroup_bpf_run_filter_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582364080,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, sockptr_t optval, sockptr_t optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1893",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_sock_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597448646,
      "name": "__cgroup_bpf_run_filter_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582530976,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1066
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492311296,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492311296,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226194640,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226194640,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1296
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285546224,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285546224,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272438528,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272438528,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931248,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931248,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877312,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877312,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922496,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922496,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982768,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1057",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982768,
      "name": "__cgroup_bpf_run_filter_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int __cgroup_bpf_run_filter_getsockopt(struct sock * sk, int level, int optname, char * optval, int * optlen, int max_optlen, int retval)
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
<li>
<b>Param type changed. </b>
<code>int * optlen</code> ➡️ <code>sockptr_t optlen</code>
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
