# Function: <code>bpf_prog_test_run_sk_lookup</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798064,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:822",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798064,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
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
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:920",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592711594,
      "name": "bpf_prog_test_run_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071590558192,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:1482",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594597633,
      "name": "bpf_prog_test_run_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071592173296,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1466
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
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:1508",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596333596,
      "name": "bpf_prog_test_run_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071594001360,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1455
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
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:1351",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596862543,
      "name": "bpf_prog_test_run_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071594377600,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1484
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
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_prog_test_run_sk_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_test_run_sk_lookup",
      "external": true,
      "loc": "net/bpf/test_run.c:1379",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597787592,
      "name": "bpf_prog_test_run_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071595178720,
      "name": "bpf_prog_test_run_sk_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1484
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog * prog, const union bpf_attr * kattr, union bpf_attr * uattr)
```
</details>
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
