# Function: <code>__inet_bind</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588459056,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:456",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588459056,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588652736,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652736,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589065344,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589065344,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289664,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289664,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590265776,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:458",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590265776,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590318816,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:461",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590318816,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590234784,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:463",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590234784,
      "name": "__inet_bind",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591018128,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:463",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591018128,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592664496,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:460",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592664496,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594532064,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:461",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594532064,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 731
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594923328,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:459",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594923328,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 731
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, u32 flags)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595735456,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:472",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595735456,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502921120,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502921120,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235614064,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235614064,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296591376,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296591376,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279013146,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279013146,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895840,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895840,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588607776,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607776,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589332224,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332224,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```

```json
{
  "name": "__inet_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589374400,
      "name": "__inet_bind",
      "external": true,
      "loc": "net/ipv4/af_inet.c:457",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_bind",
        "net/ipv4/af_inet.c:inet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374400,
      "name": "__inet_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __inet_bind(struct sock * sk, struct sockaddr * uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_bind_address_no_port</code>
</li>
<li>
<b>Param removed. </b>
<code>bool with_lock</code>
</li>
</ul>
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
