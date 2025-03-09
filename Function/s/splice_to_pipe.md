# Function: <code>splice_to_pipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194208,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "mm/shmem.c:shmem_file_splice_read",
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:vmsplice_to_pipe",
        "net/core/skbuff.c:skb_socket_splice",
        "net/unix/af_unix.c:skb_unix_socket_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194208,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358240,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "mm/shmem.c:shmem_file_splice_read",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:__generic_file_splice_read",
        "net/core/skbuff.c:skb_socket_splice",
        "net/unix/af_unix.c:skb_unix_socket_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358240,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437456,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:183",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437456,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492096,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:185",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492096,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634144,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:185",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634144,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792656,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:185",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792656,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879680,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:185",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879680,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004576,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004576,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082528,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082528,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318480,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:183",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318480,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370848,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370848,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582398160,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582398160,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719696,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719696,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264336,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583264336,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846096,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:182",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846096,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064272,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:200",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064272,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584279552,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:197",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584279552,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493616864,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493616864,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227159248,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227159248,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287204656,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287204656,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273261420,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273261420,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051264,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051264,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988816,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988816,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042544,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042544,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t splice_to_pipe(struct pipe_inode_info * pipe, struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_to_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114240,
      "name": "splice_to_pipe",
      "external": true,
      "loc": "fs/splice.c:184",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "net/core/skbuff.c:skb_splice_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114240,
      "name": "splice_to_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
