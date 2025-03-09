# Function: <code>tty_insert_flip_string_and_push_buffer</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port * port, const unsigned char * chars, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_and_push_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264992,
      "name": "tty_insert_flip_string_and_push_buffer",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:577",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264992,
      "name": "tty_insert_flip_string_and_push_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int tty_insert_flip_string_and_push_buffer(struct tty_port * port, const unsigned char * chars, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_and_push_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589679168,
      "name": "tty_insert_flip_string_and_push_buffer",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:622",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679168,
      "name": "tty_insert_flip_string_and_push_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int tty_insert_flip_string_and_push_buffer(struct tty_port * port, const unsigned char * chars, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_and_push_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589983776,
      "name": "tty_insert_flip_string_and_push_buffer",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:622",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589983776,
      "name": "tty_insert_flip_string_and_push_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int tty_insert_flip_string_and_push_buffer(struct tty_port * port, const u8 * chars, size_t size)
```

```json
{
  "name": "tty_insert_flip_string_and_push_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590322208,
      "name": "tty_insert_flip_string_and_push_buffer",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:551",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:pty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590322208,
      "name": "tty_insert_flip_string_and_push_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port * port, const unsigned char * chars, size_t size)
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
<code>const unsigned char * chars</code> ➡️ <code>const u8 * chars</code>
</li>
</ul>
</details>
</li>
</ul>
