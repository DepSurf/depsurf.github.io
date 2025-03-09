# Function: <code>tty_get_icount</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586409377,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2601",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396400,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586936186,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2599",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923104,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216784,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2572",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216784,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589626064,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2571",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589626064,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589930320,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2580",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589930320,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```

```json
{
  "name": "tty_get_icount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590268832,
      "name": "tty_get_icount",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2597",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268832,
      "name": "tty_get_icount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int tty_get_icount(struct tty_struct * tty, struct serial_icounter_struct * icount)
```
</details>
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
