# Function: <code>relay_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145680,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:566",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145680,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180496,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:577",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180496,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220752,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:560",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220752,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230496,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:560",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230496,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580281808,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:560",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281808,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580342704,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:561",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342704,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 643
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580398576,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398576,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580451584,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451584,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580500544,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500544,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580586560,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:564",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586560,
      "name": "relay_open.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    },
    {
      "addr": 18446744071580587280,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580576064,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:477",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576064,
      "name": "relay_open.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071580576624,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580578944,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:477",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578944,
      "name": "relay_open.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
    },
    {
      "addr": 18446744071580579504,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580749104,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:477",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749104,
      "name": "relay_open.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071580749744,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963312,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:477",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963312,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258496,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:474",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258496,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581353600,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:474",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353600,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459568,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:474",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459568,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491777320,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491777320,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225726204,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225726204,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284825408,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284825408,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272095016,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272095016,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580469344,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469344,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580416320,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416320,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580460592,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460592,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
struct rchan * relay_open(const char * base_filename, struct dentry * parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks * cb, void * private_data)
```

```json
{
  "name": "relay_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580516256,
      "name": "relay_open",
      "external": true,
      "loc": "kernel/relay.c:563",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516256,
      "name": "relay_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rchan_callbacks * cb</code> ➡️ <code>const struct rchan_callbacks * cb</code>
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
