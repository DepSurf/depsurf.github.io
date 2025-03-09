# Function: <code>convert___skb_to_skb</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588730679,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588954530,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589848128,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:310",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589848128,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589886672,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:393",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886672,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589792208,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:467",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589792208,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590552096,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:468",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590552096,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592165008,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:954",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592165008,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593992416,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:986",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593992416,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594369616,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:827",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594369616,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
```

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595170432,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:855",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595170432,
      "name": "convert___skb_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502556084,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235262192,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296134272,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278716066,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588560914,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588272898,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588893090,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert___skb_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589035298,
      "name": "convert___skb_to_skb",
      "external": false,
      "loc": "net/bpf/test_run.c:199",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int convert___skb_to_skb(struct sk_buff * skb, struct __sk_buff * __skb)
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
