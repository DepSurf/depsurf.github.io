# Function: <code>raw_seticmpfilter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586728734,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:784",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:compat_raw_setsockopt",
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587176944,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:787",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176944,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377104,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:791",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377104,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587511040,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:800",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511040,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588036800,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:813",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588036800,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388176,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:824",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388176,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588578752,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:816",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578752,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588986848,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588986848,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212544,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212544,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185568,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185568,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590237056,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:813",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590237056,
      "name": "raw_seticmpfilter",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590146229,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:813",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590926549,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:816",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592568404,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:789",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594428896,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:789",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594428896,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594817984,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:791",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594817984,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595629280,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:790",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595629280,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502832904,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502832904,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235533976,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296487312,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296487312,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278945212,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588818928,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818928,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530864,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530864,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255104,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255104,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```

```json
{
  "name": "raw_seticmpfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589295792,
      "name": "raw_seticmpfilter",
      "external": false,
      "loc": "net/ipv4/raw.c:812",
      "file": "net/ipv4/raw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589295792,
      "name": "raw_seticmpfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```
</details>
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
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int raw_seticmpfilter(struct sock * sk, sockptr_t optval, int optlen)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int raw_seticmpfilter(struct sock * sk, char * optval, int optlen)
```
</details>
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
