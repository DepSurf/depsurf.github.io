# Function: <code>queue_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046816,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:424",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:request_wait_answer",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046816,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260592,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:404",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260592,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350560,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:404",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350560,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582435664,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:404",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435664,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582586320,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:404",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586320,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779568,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:417",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779568,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883584,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:473",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883584,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062672,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:484",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583062672,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583172112,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172112,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583495056,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495056,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583603440,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:338",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603440,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627008,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:338",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627008,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986032,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:338",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986032,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584562512,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:334",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562512,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240080,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:334",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240080,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585469792,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:334",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469792,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int queue_interrupt(struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585704816,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:334",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704816,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494882984,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494882984,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228295840,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228295840,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288740448,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288740448,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274202516,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274202516,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583140848,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140848,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583078000,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078000,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583124880,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124880,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int queue_interrupt(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214384,
      "name": "queue_interrupt",
      "external": false,
      "loc": "fs/fuse/dev.c:332",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:request_wait_answer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214384,
      "name": "queue_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct fuse_iqueue * fiq</code>
</li>
<li>
<b>Param reordered. </b>
<code>fiq, req</code> ➡️ <code>req</code>
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
