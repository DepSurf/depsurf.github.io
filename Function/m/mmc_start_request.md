# Function: <code>mmc_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585917840,
      "name": "mmc_start_request",
      "external": false,
      "loc": "drivers/mmc/core/core.c:227",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:__mmc_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917840,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586321872,
      "name": "mmc_start_request",
      "external": false,
      "loc": "drivers/mmc/core/core.c:228",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:__mmc_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586321872,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530528,
      "name": "mmc_start_request",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530528,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586652816,
      "name": "mmc_start_request",
      "external": false,
      "loc": "drivers/mmc/core/core.c:336",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652816,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136080,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:340",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136080,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436160,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:337",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436160,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616352,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:337",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616352,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904803,
      "name": "mmc_start_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587893936,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588099488,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099488,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961440,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961440,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973136,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973136,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588861728,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:336",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588861728,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589563760,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:336",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589563760,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591058944,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:336",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591058944,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592771888,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592771888,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593208368,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593208368,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593962944,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962944,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501348952,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501348952,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233840556,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233840556,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294900160,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294900160,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277965522,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277965522,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587721056,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721056,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054016,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054016,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171552,
      "name": "mmc_start_request",
      "external": true,
      "loc": "drivers/mmc/core/core.c:335",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171552,
      "name": "mmc_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int mmc_start_request(struct mmc_host * host, struct mmc_request * mrq)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
