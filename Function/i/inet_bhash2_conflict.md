# Function: <code>inet_bhash2_conflict</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool inet_bhash2_conflict(const struct sock * sk, const struct inet_bind2_bucket * tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok)
```

```json
{
  "name": "inet_bhash2_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594209056,
      "name": "inet_bhash2_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:187",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594209056,
      "name": "inet_bhash2_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
bool inet_bhash2_conflict(const struct sock * sk, const struct inet_bind2_bucket * tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok)
```

```json
{
  "name": "inet_bhash2_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594596080,
      "name": "inet_bhash2_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:208",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594596080,
      "name": "inet_bhash2_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_bhash2_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595399776,
      "name": "inet_bhash2_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:213",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595399776,
      "name": "inet_bhash2_conflict.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool inet_bhash2_conflict(const struct sock * sk, const struct inet_bind2_bucket * tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool inet_bhash2_conflict(const struct sock * sk, const struct inet_bind2_bucket * tb2, kuid_t sk_uid, bool relax, bool reuseport_cb_ok, bool reuseport_ok)
```
</details>
</li>
</ul>
