# Function: <code>__btf_verifier_log</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707712,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:469",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707712,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784944,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:589",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784944,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870320,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870320,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921328,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921328,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071200,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:679",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071200,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086288,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1264",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086288,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105408,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1265",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105408,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335536,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1265",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335536,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640784,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1360",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640784,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031984,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1364",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031984,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224800,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1383",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224800,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380752,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:1384",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380752,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492257200,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492257200,
      "name": "__btf_verifier_log",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226147316,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226147316,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285486752,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285486752,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272397780,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272397780,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890128,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890128,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836192,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836192,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881376,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881376,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940016,
      "name": "__btf_verifier_log",
      "external": false,
      "loc": "kernel/bpf/btf.c:664",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940016,
      "name": "__btf_verifier_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __btf_verifier_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```
</details>
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
