# Function: <code>inet_reqsk_clone</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```

```json
{
  "name": "inet_reqsk_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_reqsk_clone",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:699",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734592,
      "name": "inet_reqsk_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071592714804,
      "name": "inet_reqsk_clone.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```

```json
{
  "name": "inet_reqsk_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_reqsk_clone",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:703",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364448,
      "name": "inet_reqsk_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071594600889,
      "name": "inet_reqsk_clone.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```

```json
{
  "name": "inet_reqsk_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_reqsk_clone",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:864",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594211504,
      "name": "inet_reqsk_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071596336623,
      "name": "inet_reqsk_clone.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```

```json
{
  "name": "inet_reqsk_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_reqsk_clone",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:888",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594598496,
      "name": "inet_reqsk_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071596866229,
      "name": "inet_reqsk_clone.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```

```json
{
  "name": "inet_reqsk_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_reqsk_clone",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:889",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595401744,
      "name": "inet_reqsk_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071597791304,
      "name": "inet_reqsk_clone.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct request_sock * inet_reqsk_clone(struct request_sock * req, struct sock * sk)
```
</details>
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
