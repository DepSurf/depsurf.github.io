# Function: <code>unix_msg_wait_data</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int unix_msg_wait_data(struct sock * sk, struct sk_psock * psock, long int timeo)
```

```json
{
  "name": "unix_msg_wait_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591343472,
      "name": "unix_msg_wait_data",
      "external": false,
      "loc": "net/unix/unix_bpf.c:15",
      "file": "net/unix/unix_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343472,
      "name": "unix_msg_wait_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_msg_wait_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593015871,
      "name": "unix_msg_wait_data",
      "external": false,
      "loc": "net/unix/unix_bpf.c:15",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
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
  "name": "unix_msg_wait_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594906175,
      "name": "unix_msg_wait_data",
      "external": false,
      "loc": "net/unix/unix_bpf.c:15",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
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
  "name": "unix_msg_wait_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595297703,
      "name": "unix_msg_wait_data",
      "external": false,
      "loc": "net/unix/unix_bpf.c:15",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "unix_msg_wait_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596139079,
      "name": "unix_msg_wait_data",
      "external": false,
      "loc": "net/unix/unix_bpf.c:15",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int unix_msg_wait_data(struct sock * sk, struct sk_psock * psock, long int timeo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int unix_msg_wait_data(struct sock * sk, struct sk_psock * psock, long int timeo)
```
</details>
</li>
</ul>
