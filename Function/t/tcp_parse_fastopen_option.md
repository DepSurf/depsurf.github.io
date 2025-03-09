# Function: <code>tcp_parse_fastopen_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586629388,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3676",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587077276,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3734",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587266992,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3750",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266992,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587399056,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3706",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399056,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587920304,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3655",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920304,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588269040,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3739",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269040,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588457824,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3738",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457824,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588864048,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3753",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864048,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589088256,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088256,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590052368,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3754",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052368,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590097568,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3880",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097568,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590011488,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3887",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590011488,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590782544,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3921",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590782544,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592413744,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3939",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592413744,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594268976,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3952",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594268976,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594655072,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3957",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594655072,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595459136,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4035",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595459136,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502703480,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502703480,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235405252,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235405252,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296318144,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296318144,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278834288,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278834288,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588694640,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694640,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588406624,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406624,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589130816,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130816,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```

```json
{
  "name": "tcp_parse_fastopen_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589170640,
      "name": "tcp_parse_fastopen_option",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:3760",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_parse_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170640,
      "name": "tcp_parse_fastopen_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char * cookie, bool syn, struct tcp_fastopen_cookie * foc, bool exp_opt)
```
</details>
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
