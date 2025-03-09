# Function: <code>file_fdatawait_range</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580725184,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:578",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725184,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860960,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:578",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:ksys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860960,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935552,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:555",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:ksys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935552,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581022112,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:590",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022112,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077360,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077360,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264848,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264848,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307328,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:597",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307328,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328368,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:588",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328368,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577216,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:606",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577216,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924944,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:594",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924944,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363744,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:591",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363744,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571760,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:598",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571760,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741552,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:593",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741552,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492446912,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492446912,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226316700,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226316700,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285713344,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285713344,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272517046,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272517046,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046208,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046208,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993488,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993488,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037408,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037408,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "file_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099024,
      "name": "file_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:596",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sync_file_range",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099024,
      "name": "file_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int file_fdatawait_range(struct file * file, loff_t start_byte, loff_t end_byte)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
