# Function: <code>bpf_iter_init_seq_net</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void * priv_data)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817952,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:101",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817952,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582890864,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:85",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_init_tcp",
        "net/ipv4/udp.c:bpf_iter_init_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890864,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919312,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:85",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_init_tcp",
        "net/ipv4/udp.c:bpf_iter_init_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919312,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253920,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:85",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:bpf_iter_init_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253920,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753968,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:97",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:bpf_iter_init_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753968,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369984,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:94",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:bpf_iter_init_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369984,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598304,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:94",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598304,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int bpf_iter_init_seq_net(void * priv_data, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_init_seq_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830016,
      "name": "bpf_iter_init_seq_net",
      "external": true,
      "loc": "fs/proc/proc_net.c:94",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830016,
      "name": "bpf_iter_init_seq_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_iter_init_seq_net(void * priv_data)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_iter_aux_info * aux</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
