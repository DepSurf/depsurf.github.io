# Function: <code>mptcp_crypto_key_sha</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591107968,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591107968,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190928,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190928,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128304,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128304,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591976224,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591976224,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593705504,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593705504,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595639408,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_fully_established",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595639408,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596147840,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:mptcp_subflow_fully_established",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596147840,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
```

```json
{
  "name": "mptcp_crypto_key_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597021552,
      "name": "mptcp_crypto_key_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:31",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_fully_established",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597021552,
      "name": "mptcp_crypto_key_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mptcp_crypto_key_sha(u64 key, u32 * token, u64 * idsn)
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
