# Function: <code>printk_percpu_data_ready</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026971,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:470",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024336,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006393,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:450",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002336,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008121,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:438",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003728,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580140250,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:433",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592133669,
      "name": "printk_percpu_data_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580135328,
      "name": "printk_percpu_data_ready",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580283978,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:438",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904391,
      "name": "printk_percpu_data_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580277776,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580493593,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:519",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:_printk_deferred",
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985551,
      "name": "printk_percpu_data_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580486336,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580565433,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:506",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:_printk_deferred",
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596503861,
      "name": "printk_percpu_data_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580558288,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool printk_percpu_data_ready()
```

```json
{
  "name": "printk_percpu_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628277,
      "name": "printk_percpu_data_ready",
      "external": true,
      "loc": "kernel/printk/printk.c:506",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401286,
      "name": "printk_percpu_data_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580615312,
      "name": "printk_percpu_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool printk_percpu_data_ready()
```
</details>
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
