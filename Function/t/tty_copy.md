# Function: <code>tty_copy</code>

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
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534992,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:167",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534992,
      "name": "tty_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586420601,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:168",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947639,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:168",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588241632,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:168",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588241632,
      "name": "tty_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653216,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:171",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653216,
      "name": "tty_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589957088,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:170",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589957088,
      "name": "tty_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void tty_copy(const struct tty_struct * tty, void * to, size_t tail, size_t n)
```

```json
{
  "name": "tty_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590294656,
      "name": "tty_copy",
      "external": false,
      "loc": "drivers/tty/n_tty.c:167",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf",
        "drivers/tty/n_tty.c:canon_copy_from_read_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590294656,
      "name": "tty_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tty_copy(struct tty_struct * tty, void * to, size_t tail, size_t n)
```
</details>
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
<code>struct tty_struct * tty</code> ➡️ <code>const struct tty_struct * tty</code>
</li>
</ul>
</details>
</li>
</ul>
