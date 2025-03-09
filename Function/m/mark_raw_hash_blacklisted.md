# Function: <code>mark_raw_hash_blacklisted</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mark_raw_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_raw_hash_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581918860,
      "name": "mark_raw_hash_blacklisted",
      "external": false,
      "loc": "certs/blacklist.c:182",
      "file": "certs/blacklist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "certs/blacklist.c:mark_hash_blacklisted"
      ],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918448,
      "name": "mark_raw_hash_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071593964311,
      "name": "mark_raw_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mark_raw_hash_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627842185,
      "name": "mark_raw_hash_blacklisted",
      "external": false,
      "loc": "certs/blacklist.c:182",
      "file": "certs/blacklist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "certs/blacklist.c:blacklist_init",
        "certs/blacklist.c:mark_hash_blacklisted"
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
int mark_raw_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_raw_hash_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556576,
      "name": "mark_raw_hash_blacklisted",
      "external": false,
      "loc": "certs/blacklist.c:182",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556576,
      "name": "mark_raw_hash_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int mark_raw_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_raw_hash_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727360,
      "name": "mark_raw_hash_blacklisted",
      "external": false,
      "loc": "certs/blacklist.c:182",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init",
        "certs/blacklist.c:mark_hash_blacklisted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727360,
      "name": "mark_raw_hash_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int mark_raw_hash_blacklisted(const char * hash)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int mark_raw_hash_blacklisted(const char * hash)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int mark_raw_hash_blacklisted(const char * hash)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
