# Function: <code>lookup_one_common</code>

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
int lookup_one_common(struct user_namespace * mnt_userns, const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524496,
      "name": "lookup_one_common",
      "external": false,
      "loc": "fs/namei.c:2600",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524496,
      "name": "lookup_one_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int lookup_one_common(struct user_namespace * mnt_userns, const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045984,
      "name": "lookup_one_common",
      "external": false,
      "loc": "fs/namei.c:2646",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045984,
      "name": "lookup_one_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int lookup_one_common(struct user_namespace * mnt_userns, const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583611504,
      "name": "lookup_one_common",
      "external": false,
      "loc": "fs/namei.c:2625",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611504,
      "name": "lookup_one_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int lookup_one_common(struct mnt_idmap * idmap, const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824576,
      "name": "lookup_one_common",
      "external": false,
      "loc": "fs/namei.c:2656",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824576,
      "name": "lookup_one_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int lookup_one_common(struct mnt_idmap * idmap, const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030640,
      "name": "lookup_one_common",
      "external": false,
      "loc": "fs/namei.c:2673",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030640,
      "name": "lookup_one_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int lookup_one_common(struct user_namespace * mnt_userns, const char * name, struct dentry * base, int len, struct qstr * this)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
