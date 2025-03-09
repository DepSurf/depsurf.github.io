# Function: <code>tcp_fastopen_cookie_gen_check</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588974766,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589199488,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tcp_fastopen_cookie_gen_check(struct sock * sk, struct request_sock * req, struct sk_buff * syn, struct tcp_fastopen_cookie * orig, struct tcp_fastopen_cookie * valid_foc)
```

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590170336,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:227",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590170336,
      "name": "tcp_fastopen_cookie_gen_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int tcp_fastopen_cookie_gen_check(struct sock * sk, struct request_sock * req, struct sk_buff * syn, struct tcp_fastopen_cookie * orig, struct tcp_fastopen_cookie * valid_foc)
```

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590219488,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:227",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219488,
      "name": "tcp_fastopen_cookie_gen_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590134636,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:227",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590914722,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:216",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592554651,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:210",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594414091,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:210",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594803470,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:210",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595614670,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:210",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502819472,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235520896,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296466724,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278933628,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588805872,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588517808,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589242048,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_cookie_gen_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589282558,
      "name": "tcp_fastopen_cookie_gen_check",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:204",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int tcp_fastopen_cookie_gen_check(struct sock * sk, struct request_sock * req, struct sk_buff * syn, struct tcp_fastopen_cookie * orig, struct tcp_fastopen_cookie * valid_foc)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int tcp_fastopen_cookie_gen_check(struct sock * sk, struct request_sock * req, struct sk_buff * syn, struct tcp_fastopen_cookie * orig, struct tcp_fastopen_cookie * valid_foc)
```
</details>
</li>
</ul>
