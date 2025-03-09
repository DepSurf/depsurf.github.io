# Struct: <code>rpc_credops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
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
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
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
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
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
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind;
    __be32 * (*)(struct rpc_task *, __be32 *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    __be32 * (*)(struct rpc_task *, __be32 *) crvalidate;
    int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req;
    int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    bool (*)(struct rpc_cred *) crkey_to_expire;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
}
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct rpc_task *) crneed_reencode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rpc_cred * (*)(struct rpc_task *, struct rpc_cred *, int) crbind</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct rpc_cred *) crkey_to_expire</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__be32 * (*)(struct rpc_task *, __be32 *) crmarshal</code> ➡️ <code>int (*)(struct rpc_task *, struct xdr_stream *) crmarshal</code>
</li>
<li>
<b>Field type changed. </b>
<code>__be32 * (*)(struct rpc_task *, __be32 *) crvalidate</code> ➡️ <code>int (*)(struct rpc_task *, struct xdr_stream *) crvalidate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct rpc_task *, kxdreproc_t, void *, __be32 *, void *) crwrap_req</code> ➡️ <code>int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct rpc_task *, kxdrdproc_t, void *, __be32 *, void *) crunwrap_resp</code> ➡️ <code>int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_credops {
    const char * cr_name;
    int (*)(struct rpc_auth *, struct rpc_cred *) cr_init;
    void (*)(struct rpc_cred *) crdestroy;
    int (*)(struct auth_cred *, struct rpc_cred *, int) crmatch;
    int (*)(struct rpc_task *, struct xdr_stream *) crmarshal;
    int (*)(struct rpc_task *) crrefresh;
    int (*)(struct rpc_task *, struct xdr_stream *) crvalidate;
    int (*)(struct rpc_task *, struct xdr_stream *) crwrap_req;
    int (*)(struct rpc_task *, struct xdr_stream *) crunwrap_resp;
    int (*)(struct rpc_cred *) crkey_timeout;
    char * (*)(struct rpc_cred *) crstringify_acceptor;
    bool (*)(struct rpc_task *) crneed_reencode;
}
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
