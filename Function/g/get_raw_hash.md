# Function: <code>get_raw_hash</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * get_raw_hash(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "get_raw_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918256,
      "name": "get_raw_hash",
      "external": false,
      "loc": "certs/blacklist.c:146",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918256,
      "name": "get_raw_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
char * get_raw_hash(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "get_raw_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353824,
      "name": "get_raw_hash",
      "external": false,
      "loc": "certs/blacklist.c:146",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353824,
      "name": "get_raw_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
char * get_raw_hash(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "get_raw_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556912,
      "name": "get_raw_hash",
      "external": false,
      "loc": "certs/blacklist.c:146",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556912,
      "name": "get_raw_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
char * get_raw_hash(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "get_raw_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727696,
      "name": "get_raw_hash",
      "external": false,
      "loc": "certs/blacklist.c:146",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727696,
      "name": "get_raw_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
char * get_raw_hash(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```
</details>
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
