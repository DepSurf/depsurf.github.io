# Function: <code>iterate_tty_read</code>

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
int iterate_tty_read(struct tty_ldisc * ld, struct tty_struct * tty, struct file * file, struct iov_iter * to)
```

```json
{
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586515696,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:844",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586515696,
      "name": "iterate_tty_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586400778,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:860",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
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
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586927466,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:855",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
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
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588221578,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:845",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589635172,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:839",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589938816,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:848",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iterate_tty_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590277696,
      "name": "iterate_tty_read",
      "external": false,
      "loc": "drivers/tty/tty_io.c:850",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int iterate_tty_read(struct tty_ldisc * ld, struct tty_struct * tty, struct file * file, struct iov_iter * to)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int iterate_tty_read(struct tty_ldisc * ld, struct tty_struct * tty, struct file * file, struct iov_iter * to)
```
</details>
</li>
</ul>
