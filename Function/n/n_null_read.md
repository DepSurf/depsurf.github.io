# Function: <code>n_null_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602672,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:34",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602672,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585015136,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015136,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585249280,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585249280,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368704,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368704,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585582368,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582368,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585723280,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723280,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586454048,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586454048,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586568416,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568416,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586453168,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453168,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980112,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980112,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588277136,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277136,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589692416,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692416,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589997088,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589997088,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, u8 * buf, size_t nr, void * * cookie, long unsigned int offset)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590335408,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:13",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590335408,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498418584,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498418584,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231088048,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231088048,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291602080,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291602080,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276073102,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276073102,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484304,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484304,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354192,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354192,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673680,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673680,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```

```json
{
  "name": "n_null_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781760,
      "name": "n_null_read",
      "external": false,
      "loc": "drivers/tty/n_null.c:22",
      "file": "drivers/tty/n_null.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781760,
      "name": "n_null_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t n_null_read(struct tty_struct * tty, struct file * file, unsigned char * buf, size_t nr)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * * cookie</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char * buf</code> ➡️ <code>u8 * buf</code>
</li>
</ul>
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
