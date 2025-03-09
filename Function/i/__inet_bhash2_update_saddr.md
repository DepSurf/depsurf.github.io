# Function: <code>__inet_bhash2_update_saddr</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __inet_bhash2_update_saddr(struct sock * sk, void * saddr, int family, bool reset)
```

```json
{
  "name": "__inet_bhash2_update_saddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_bhash2_update_saddr",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:888",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199536,
      "name": "__inet_bhash2_update_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071596336528,
      "name": "__inet_bhash2_update_saddr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int __inet_bhash2_update_saddr(struct sock * sk, void * saddr, int family, bool reset)
```

```json
{
  "name": "__inet_bhash2_update_saddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594586752,
      "name": "__inet_bhash2_update_saddr",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:878",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594586752,
      "name": "__inet_bhash2_update_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1232
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
int __inet_bhash2_update_saddr(struct sock * sk, void * saddr, int family, bool reset)
```

```json
{
  "name": "__inet_bhash2_update_saddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595390160,
      "name": "__inet_bhash2_update_saddr",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:890",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595390160,
      "name": "__inet_bhash2_update_saddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1293
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
int __inet_bhash2_update_saddr(struct sock * sk, void * saddr, int family, bool reset)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
