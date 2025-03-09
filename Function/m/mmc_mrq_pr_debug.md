# Function: <code>mmc_mrq_pr_debug</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586652865,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:266",
      "file": "drivers/mmc/core/core.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128112,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:269",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128112,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428096,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:266",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428096,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587608944,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:266",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608944,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887104,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887104,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093344,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093344,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588955376,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588955376,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967792,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967792,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856320,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:265",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856320,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557696,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:265",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557696,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591051616,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:265",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591051616,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592764080,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592764080,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593200224,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593200224,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593954800,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593954800,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501341728,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501341728,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233834604,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233834604,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294891648,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294891648,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277959136,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277959136,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587714912,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587714912,
      "name": "mmc_mrq_pr_debug",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588047872,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588047872,
      "name": "mmc_mrq_pr_debug",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```

```json
{
  "name": "mmc_mrq_pr_debug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165296,
      "name": "mmc_mrq_pr_debug",
      "external": false,
      "loc": "drivers/mmc/core/core.c:264",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:mmc_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165296,
      "name": "mmc_mrq_pr_debug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
```
</details>
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
void mmc_mrq_pr_debug(struct mmc_host * host, struct mmc_request * mrq, bool cqe)
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
