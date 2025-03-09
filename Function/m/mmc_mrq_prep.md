# Function: <code>mmc_mrq_prep</code>

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
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586652935,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:296",
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128656,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:303",
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
      "addr": 18446744071587128656,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428560,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:300",
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
      "addr": 18446744071587428560,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587609408,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:300",
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
      "addr": 18446744071587609408,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887616,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071587887616,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093808,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071588093808,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588955840,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071588955840,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968256,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071588968256,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856784,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:299",
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
      "addr": 18446744071588856784,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589558864,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:299",
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
      "addr": 18446744071589558864,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591052800,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:299",
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
      "addr": 18446744071591052800,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592765328,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071592765328,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593201504,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071593201504,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593956080,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071593956080,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501342192,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446603336501342192,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233835172,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 3233835172,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294892320,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 13835058055294892320,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277959586,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446743936277959586,
      "name": "mmc_mrq_prep",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715376,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071587715376,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048336,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071588048336,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_mrq_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165760,
      "name": "mmc_mrq_prep",
      "external": false,
      "loc": "drivers/mmc/core/core.c:298",
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
      "addr": 18446744071588165760,
      "name": "mmc_mrq_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
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
int mmc_mrq_prep(struct mmc_host * host, struct mmc_request * mrq)
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
