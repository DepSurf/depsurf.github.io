# Function: <code>tun_detach_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585070960,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:1800",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452048,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:1909",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452048,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585656144,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:1900",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656144,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742592,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:1947",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742592,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176768,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2416",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176768,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586431104,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2763",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431104,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576832,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2925",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576832,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828784,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2923",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828784,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974864,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974864,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587804139,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2904",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach_filter"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587861899,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2826",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach_filter"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587762888,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2831",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588358976,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2839",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589748164,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2889",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591366300,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2902",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591728433,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2923",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592472335,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2935",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499966280,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499966280,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232506892,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232506892,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293295648,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293295648,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277045632,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277045632,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586731872,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731872,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599088,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599088,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586929424,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929424,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
```

```json
{
  "name": "tun_detach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036848,
      "name": "tun_detach_filter",
      "external": false,
      "loc": "drivers/net/tun.c:2927",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036848,
      "name": "tun_detach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tun_detach_filter(struct tun_struct * tun, int n)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tun_detach_filter(struct tun_struct * tun, int n)
```
</details>
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
