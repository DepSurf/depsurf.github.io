# Function: <code>bpf_cgroup_storage_release</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779872,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:426",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779872,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865510,
      "name": "bpf_cgroup_storage_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580864528,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915552,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915552,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void bpf_cgroup_storage_release(struct bpf_prog_aux * aux, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062624,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_free_used_maps",
        "kernel/bpf/core.c:__bpf_free_used_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062624,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492249248,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492249248,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226141972,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226141972,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285477856,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285477856,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272391786,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272391786,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884352,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884352,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830416,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830416,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875600,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875600,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```

```json
{
  "name": "bpf_cgroup_storage_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934240,
      "name": "bpf_cgroup_storage_release",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:446",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934240,
      "name": "bpf_cgroup_storage_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog * prog, struct bpf_map * _map)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog_aux * aux</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog * prog</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog_aux * aux, struct bpf_map * _map)
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
