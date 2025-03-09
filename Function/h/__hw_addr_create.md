# Function: <code>__hw_addr_create</code>

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
  "name": "__hw_addr_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590019254,
      "name": "__hw_addr_create",
      "external": false,
      "loc": "net/core/dev_addr_lists.c:20",
      "file": "net/core/dev_addr_lists.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:__hw_addr_add_ex"
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
  "name": "__hw_addr_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591559229,
      "name": "__hw_addr_create",
      "external": false,
      "loc": "net/core/dev_addr_lists.c:51",
      "file": "net/core/dev_addr_lists.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:__hw_addr_add_ex"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_hw_addr * __hw_addr_create(const unsigned char * addr, int addr_len, unsigned char addr_type, bool global, bool sync)
```

```json
{
  "name": "__hw_addr_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hw_addr_create",
      "external": false,
      "loc": "net/core/dev_addr_lists.c:51",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_addr_lists.c:__hw_addr_add_ex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593336288,
      "name": "__hw_addr_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596325443,
      "name": "__hw_addr_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct netdev_hw_addr * __hw_addr_create(const unsigned char * addr, int addr_len, unsigned char addr_type, bool global, bool sync)
```

```json
{
  "name": "__hw_addr_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hw_addr_create",
      "external": false,
      "loc": "net/core/dev_addr_lists.c:51",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_addr_lists.c:__hw_addr_add_ex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593798064,
      "name": "__hw_addr_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596855680,
      "name": "__hw_addr_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct netdev_hw_addr * __hw_addr_create(const unsigned char * addr, int addr_len, unsigned char addr_type, bool global, bool sync)
```

```json
{
  "name": "__hw_addr_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hw_addr_create",
      "external": false,
      "loc": "net/core/dev_addr_lists.c:51",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_addr_lists.c:__hw_addr_add_ex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594579408,
      "name": "__hw_addr_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071597780652,
      "name": "__hw_addr_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct netdev_hw_addr * __hw_addr_create(const unsigned char * addr, int addr_len, unsigned char addr_type, bool global, bool sync)
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
