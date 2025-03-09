# Function: <code>tcp_update_ulp</code>

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
void tcp_update_ulp(struct sock * sk, struct proto * proto)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979312,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979312,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203760,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203760,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176048,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176048,
      "name": "tcp_update_ulp",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590225216,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590225216,
      "name": "tcp_update_ulp",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139296,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139296,
      "name": "tcp_update_ulp",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590919600,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590919600,
      "name": "tcp_update_ulp",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592559904,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592559904,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594419680,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594419680,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594809024,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594809024,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595620272,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:103",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_update_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595620272,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502824600,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502824600,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235526296,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235526296,
      "name": "tcp_update_ulp",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296473680,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296473680,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278938028,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278938028,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588810144,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588810144,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522080,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522080,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246320,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246320,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tcp_update_ulp(struct sock * sk, struct proto * proto, void (*)(struct sock *) write_space)
```

```json
{
  "name": "tcp_update_ulp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286912,
      "name": "tcp_update_ulp",
      "external": true,
      "loc": "net/ipv4/tcp_ulp.c:99",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286912,
      "name": "tcp_update_ulp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void tcp_update_ulp(struct sock * sk, struct proto * proto)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*)(struct sock *) write_space</code>
</li>
</ul>
</details>
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
