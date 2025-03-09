# Function: <code>mptcp_setsockopt</code>

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
int mptcp_setsockopt(struct sock * sk, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591076912,
      "name": "mptcp_setsockopt",
      "external": false,
      "loc": "net/mptcp/protocol.c:1560",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591076912,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591143760,
      "name": "mptcp_setsockopt",
      "external": false,
      "loc": "net/mptcp/protocol.c:2866",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591143760,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591151648,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:569",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591151648,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592003072,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:611",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592003072,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593740864,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:804",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593740864,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 777
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595677344,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:821",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595677344,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 777
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596187696,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:825",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596187696,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597062928,
      "name": "mptcp_setsockopt",
      "external": true,
      "loc": "net/mptcp/sockopt.c:840",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597062928,
      "name": "mptcp_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int mptcp_setsockopt(struct sock * sk, int level, int optname, char * optval, unsigned int optlen)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
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
