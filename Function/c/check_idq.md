# Function: <code>check_idq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_idq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581405680,
      "name": "check_idq",
      "external": false,
      "loc": "fs/quota/dquot.c:1270",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405680,
      "name": "check_idq.constprop.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_idq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581587168,
      "name": "check_idq",
      "external": false,
      "loc": "fs/quota/dquot.c:1279",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587168,
      "name": "check_idq.constprop.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_idq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581675552,
      "name": "check_idq",
      "external": false,
      "loc": "fs/quota/dquot.c:1276",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675552,
      "name": "check_idq.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int check_idq(struct dquot * dquot, qsize_t inodes, struct dquot_warn * warn)
```

```json
{
  "name": "check_idq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730384,
      "name": "check_idq",
      "external": false,
      "loc": "fs/quota/dquot.c:1282",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730384,
      "name": "check_idq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int check_idq(struct dquot * dquot, qsize_t inodes, struct dquot_warn * warn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int check_idq(struct dquot * dquot, qsize_t inodes, struct dquot_warn * warn)
```
</details>
</li>
</ul>
