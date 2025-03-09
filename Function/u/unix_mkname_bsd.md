# Function: <code>unix_mkname_bsd</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_mkname_bsd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592992677,
      "name": "unix_mkname_bsd",
      "external": false,
      "loc": "net/unix/af_unix.c:285",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
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
  "name": "unix_mkname_bsd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594887541,
      "name": "unix_mkname_bsd",
      "external": false,
      "loc": "net/unix/af_unix.c:291",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int unix_mkname_bsd(struct sockaddr_un * sunaddr, int addr_len)
```

```json
{
  "name": "unix_mkname_bsd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595266432,
      "name": "unix_mkname_bsd",
      "external": false,
      "loc": "net/unix/af_unix.c:292",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595266432,
      "name": "unix_mkname_bsd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int unix_mkname_bsd(struct sockaddr_un * sunaddr, int addr_len)
```

```json
{
  "name": "unix_mkname_bsd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596107280,
      "name": "unix_mkname_bsd",
      "external": false,
      "loc": "net/unix/af_unix.c:291",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596107280,
      "name": "unix_mkname_bsd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int unix_mkname_bsd(struct sockaddr_un * sunaddr, int addr_len)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
