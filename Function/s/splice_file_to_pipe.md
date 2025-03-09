# Function: <code>splice_file_to_pipe</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405568,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1008",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405568,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727344,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1010",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727344,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272880,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1006",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272880,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855248,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1005",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855248,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075888,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1226",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075888,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
ssize_t splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
```

```json
{
  "name": "splice_file_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292000,
      "name": "splice_file_to_pipe",
      "external": true,
      "loc": "fs/splice.c:1285",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292000,
      "name": "splice_file_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
long int splice_file_to_pipe(struct file * in, struct pipe_inode_info * opipe, loff_t * offset, size_t len, unsigned int flags)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
