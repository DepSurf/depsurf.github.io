# Function: <code>prb_init</code>

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
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013168,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2034",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013168,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014064,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2034",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014064,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2034",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592137439,
      "name": "prb_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071580146000,
      "name": "prb_init",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2075",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593908194,
      "name": "prb_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071580290320,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2075",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595988850,
      "name": "prb_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071580500656,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2075",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596506519,
      "name": "prb_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071580572432,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```

```json
{
  "name": "prb_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_init",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:2075",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597404184,
      "name": "prb_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071580636672,
      "name": "prb_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void prb_init(struct printk_ringbuffer * rb, char * text_buf, unsigned int textbits, struct prb_desc * descs, unsigned int descbits, struct printk_info * infos)
```
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
