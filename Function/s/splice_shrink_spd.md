# Function: <code>splice_shrink_spd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581198176,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:294",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:vmsplice_to_pipe"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "mm/shmem.c:shmem_file_splice_read",
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:vmsplice_to_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198176,
      "name": "splice_shrink_spd.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581201840,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581366374,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:297",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:__generic_file_splice_read"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "mm/shmem.c:shmem_file_splice_read",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:__generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361312,
      "name": "splice_shrink_spd.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581366512,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444176,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444176,
      "name": "splice_shrink_spd",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498528,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498528,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640656,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640656,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802912,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:274",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802912,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889920,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:274",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889920,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015008,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015008,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092976,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092976,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582327472,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:277",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327472,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378512,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378512,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405376,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405376,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727152,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727152,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272656,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272656,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854992,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:276",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854992,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074144,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:294",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074144,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290256,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:292",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290256,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493628592,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493628592,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227168008,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227168008,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287218896,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287218896,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273267992,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273267992,
      "name": "splice_shrink_spd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061712,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061712,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999264,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999264,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052992,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052992,
      "name": "splice_shrink_spd",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc * spd)
```

```json
{
  "name": "splice_shrink_spd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124672,
      "name": "splice_shrink_spd",
      "external": true,
      "loc": "fs/splice.c:273",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124672,
      "name": "splice_shrink_spd",
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
