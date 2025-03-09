# Function: <code>pipe_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026768,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:77",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026768,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187012,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:78",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185888,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264228,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:78",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263104,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581313172,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:78",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312144,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581453348,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:79",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452176,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581612980,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:74",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611808,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699332,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:74",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698160,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581817073,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815792,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581889633,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888352,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117142,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:78",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115792,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582163523,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:78",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162224,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188019,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:93",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186736,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582505395,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:93",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504112,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031379,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:94",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027344,
      "name": "pipe_unlock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583595651,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:94",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591440,
      "name": "pipe_unlock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812419,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:94",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808000,
      "name": "pipe_unlock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584018419,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:94",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014224,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493367644,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493365432,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226954740,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226953108,
      "name": "pipe_unlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286913956,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286911232,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273087340,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273085730,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581858369,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857088,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795969,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794688,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581849681,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848400,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_unlock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919185,
      "name": "pipe_unlock",
      "external": true,
      "loc": "fs/pipe.c:75",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917920,
      "name": "pipe_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
