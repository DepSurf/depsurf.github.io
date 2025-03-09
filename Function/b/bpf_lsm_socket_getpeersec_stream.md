# Function: <code>bpf_lsm_socket_getpeersec_stream</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, char * optval, int * optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176512,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:294",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176512,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, char * optval, int * optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194928,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:304",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194928,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, char * optval, int * optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435248,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:304",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435248,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, char * optval, int * optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764800,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:303",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764800,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, sockptr_t optval, sockptr_t optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184704,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:311",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184704,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, sockptr_t optval, sockptr_t optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384496,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:312",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384496,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, sockptr_t optval, sockptr_t optlen, unsigned int len)
```

```json
{
  "name": "bpf_lsm_socket_getpeersec_stream",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552096,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "external": true,
      "loc": "include/linux/lsm_hook_defs.h:322",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552096,
      "name": "bpf_lsm_socket_getpeersec_stream",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket * sock, char * optval, int * optlen, unsigned int len)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
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
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
