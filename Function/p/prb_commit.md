# Function: <code>prb_commit</code>

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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011472,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1626",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011472,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011808,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1626",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011808,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1626",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592136286,
      "name": "prb_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071580143440,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593907378,
      "name": "prb_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580288224,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595988137,
      "name": "prb_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580498352,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596505846,
      "name": "prb_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580570128,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void prb_commit(struct prb_reserved_entry * e)
```

```json
{
  "name": "prb_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_commit",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597403511,
      "name": "prb_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580634368,
      "name": "prb_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void prb_commit(struct prb_reserved_entry * e)
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
