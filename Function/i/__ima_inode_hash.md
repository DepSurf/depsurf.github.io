# Function: <code>__ima_inode_hash</code>

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
int __ima_inode_hash(struct inode * inode, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293392,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:504",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293392,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __ima_inode_hash(struct inode * inode, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584327312,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:505",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327312,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __ima_inode_hash(struct inode * inode, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714800,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:522",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714800,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int __ima_inode_hash(struct inode * inode, struct file * file, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585389200,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:525",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389200,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int __ima_inode_hash(struct inode * inode, struct file * file, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141776,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:530",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141776,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int __ima_inode_hash(struct inode * inode, struct file * file, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379888,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:549",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379888,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int __ima_inode_hash(struct inode * inode, struct file * file, char * buf, size_t buf_size)
```

```json
{
  "name": "__ima_inode_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644480,
      "name": "__ima_inode_hash",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:563",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_inode_hash",
        "security/integrity/ima/ima_main.c:ima_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644480,
      "name": "__ima_inode_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __ima_inode_hash(struct inode * inode, char * buf, size_t buf_size)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, buf, buf_size</code> ➡️ <code>inode, file, buf, buf_size</code>
</li>
</ul>
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
