# Function: <code>SYSC_newfstatat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```

```json
{
  "name": "SYSC_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014992,
      "name": "SYSC_newfstatat",
      "external": false,
      "loc": "fs/stat.c:291",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SyS_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014992,
      "name": "SYSC_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```

```json
{
  "name": "SYSC_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173376,
      "name": "SYSC_newfstatat",
      "external": false,
      "loc": "fs/stat.c:291",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SyS_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173376,
      "name": "SYSC_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```

```json
{
  "name": "SYSC_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250368,
      "name": "SYSC_newfstatat",
      "external": false,
      "loc": "fs/stat.c:291",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SyS_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250368,
      "name": "SYSC_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```

```json
{
  "name": "SYSC_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298256,
      "name": "SYSC_newfstatat",
      "external": false,
      "loc": "fs/stat.c:357",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SyS_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298256,
      "name": "SYSC_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```

```json
{
  "name": "SYSC_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438112,
      "name": "SYSC_newfstatat",
      "external": false,
      "loc": "fs/stat.c:358",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SyS_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438112,
      "name": "SYSC_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int SYSC_newfstatat(int dfd, const char * filename, struct stat * statbuf, int flag)
```
</details>
</li>
</ul>
