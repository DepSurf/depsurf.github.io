# Function: <code>md5_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582962336,
      "name": "md5_transform",
      "external": true,
      "loc": "lib/md5.c:13",
      "file": "lib/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update",
        "drivers/char/random.c:get_random_int",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962336,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1971
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249856,
      "name": "md5_transform",
      "external": true,
      "loc": "lib/md5.c:13",
      "file": "lib/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update",
        "drivers/char/random.c:get_random_long",
        "drivers/char/random.c:get_random_int",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249856,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1872
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365168,
      "name": "md5_transform",
      "external": true,
      "loc": "lib/md5.c:13",
      "file": "lib/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update",
        "drivers/char/random.c:get_random_long",
        "drivers/char/random.c:get_random_int",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365168,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1872
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073792,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:60",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073792,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240224,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:60",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240224,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447936,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447936,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569904,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569904,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583758880,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758880,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868560,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868560,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258720,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258720,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1795
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377424,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377424,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1795
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584411920,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411920,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1794
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807520,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807520,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1794
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585497840,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585497840,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260720,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260720,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586501520,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586501520,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770912,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:40",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770912,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495686848,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495686848,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2556
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229036864,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229036864,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2620
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289831504,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289831504,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2444
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274834620,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274834620,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2984
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837296,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837296,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774352,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774352,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821056,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821056,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void md5_transform(__u32 * hash, const __u32 * in)
```

```json
{
  "name": "md5_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922128,
      "name": "md5_transform",
      "external": false,
      "loc": "crypto/md5.c:43",
      "file": "crypto/md5.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_final",
        "crypto/md5.c:md5_update",
        "crypto/md5.c:md5_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922128,
      "name": "md5_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
