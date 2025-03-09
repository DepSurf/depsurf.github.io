# Function: <code>safesetid_file_write</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667344,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583668166,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773616,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583774438,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164656,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164656,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495575216,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495575216,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228937272,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228937272,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289670992,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289670992,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274742452,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274742452,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742352,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583743174,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679408,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583680230,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726128,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583726950,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "safesetid_file_write",
      "external": false,
      "loc": "security/safesetid/securityfs.c:195",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826880,
      "name": "safesetid_file_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071583827702,
      "name": "safesetid_file_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t safesetid_file_write(struct file * file, const char * buf, size_t len, loff_t * ppos)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
