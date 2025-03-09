# Function: <code>mptcp_crypto_hmac_sha</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:47",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591108882,
      "name": "mptcp_crypto_hmac_sha.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591108192,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591640932,
      "name": "mptcp_crypto_hmac_sha.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591191056,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591584427,
      "name": "mptcp_crypto_hmac_sha.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591128432,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754748,
      "name": "mptcp_crypto_hmac_sha.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591976352,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641774,
      "name": "mptcp_crypto_hmac_sha.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071593705680,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595639600,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595639600,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1089
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596148032,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596148032,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
```

```json
{
  "name": "mptcp_crypto_hmac_sha",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597021744,
      "name": "mptcp_crypto_hmac_sha",
      "external": true,
      "loc": "net/mptcp/crypto.c:44",
      "file": "net/mptcp/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:add_addr_generate_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597021744,
      "name": "mptcp_crypto_hmac_sha",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
void mptcp_crypto_hmac_sha(u64 key1, u64 key2, u8 * msg, int len, void * hmac)
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
