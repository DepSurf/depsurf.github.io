# Function: <code>inet_ehash_lookup_by_sk</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool inet_ehash_lookup_by_sk(struct sock * sk, struct hlist_nulls_head * list)
```

```json
{
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039824,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:517",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039824,
      "name": "inet_ehash_lookup_by_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589959756,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:517",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590726860,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:519",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592356047,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:479",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594196325,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:595",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594583464,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:595",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
  "name": "inet_ehash_lookup_by_sk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595387240,
      "name": "inet_ehash_lookup_by_sk",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:616",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool inet_ehash_lookup_by_sk(struct sock * sk, struct hlist_nulls_head * list)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool inet_ehash_lookup_by_sk(struct sock * sk, struct hlist_nulls_head * list)
```
</details>
</li>
</ul>
