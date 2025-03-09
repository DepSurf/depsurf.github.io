# Function: <code>fib_find_matching_alias</code>

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
struct fib_alias * fib_find_matching_alias(struct net * net, const struct fib_rt_info * fri)
```

```json
{
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323008,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1011",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323008,
      "name": "fib_find_matching_alias",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct fib_alias * fib_find_matching_alias(struct net * net, const struct fib_rt_info * fri)
```

```json
{
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590376016,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1011",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376016,
      "name": "fib_find_matching_alias",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590291494,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1011",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591074809,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1011",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592724380,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1016",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594594876,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1016",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594986636,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1016",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
  "name": "fib_find_matching_alias",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595799132,
      "name": "fib_find_matching_alias",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:1017",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct fib_alias * fib_find_matching_alias(struct net * net, const struct fib_rt_info * fri)
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
struct fib_alias * fib_find_matching_alias(struct net * net, const struct fib_rt_info * fri)
```
</details>
</li>
</ul>
