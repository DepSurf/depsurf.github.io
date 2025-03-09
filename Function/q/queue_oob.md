# Function: <code>queue_oob</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_oob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591333873,
      "name": "queue_oob",
      "external": false,
      "loc": "net/unix/af_unix.c:1965",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg"
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
  "name": "queue_oob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593006709,
      "name": "queue_oob",
      "external": false,
      "loc": "net/unix/af_unix.c:2052",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_sendmsg"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int queue_oob(struct socket * sock, struct msghdr * msg, struct sock * other)
```

```json
{
  "name": "queue_oob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594886912,
      "name": "queue_oob",
      "external": false,
      "loc": "net/unix/af_unix.c:2107",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594886912,
      "name": "queue_oob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int queue_oob(struct socket * sock, struct msghdr * msg, struct sock * other, struct scm_cookie * scm, bool fds_sent)
```

```json
{
  "name": "queue_oob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595284416,
      "name": "queue_oob",
      "external": false,
      "loc": "net/unix/af_unix.c:2117",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595284416,
      "name": "queue_oob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int queue_oob(struct socket * sock, struct msghdr * msg, struct sock * other, struct scm_cookie * scm, bool fds_sent)
```

```json
{
  "name": "queue_oob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596122256,
      "name": "queue_oob",
      "external": false,
      "loc": "net/unix/af_unix.c:2123",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596122256,
      "name": "queue_oob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int queue_oob(struct socket * sock, struct msghdr * msg, struct sock * other)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scm_cookie * scm</code>
</li>
<li>
<b>Param added. </b>
<code>bool fds_sent</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
