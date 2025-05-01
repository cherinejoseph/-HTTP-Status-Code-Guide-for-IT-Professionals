# 🔧 HTTP Status Code Guide for IT Professionals

A practical and developer-focused cheat sheet for HTTP status codes, including explanations, use cases, and actionable resolutions. Perfect for web developers, DevOps engineers, sysadmins, and API designers.

---

## 📘 Overview

HTTP status codes are responses issued by a server in response to a client's request. This guide covers the most commonly encountered codes and includes **next steps or resolutions** for troubleshooting.

---

## ✅ 2xx – Success

| Code | Meaning           | Action / Resolution                          |
|------|-------------------|----------------------------------------------|
| 200  | OK                | ✅ Everything worked. No action needed.       |
| 201  | Created           | 🔄 Resource created. Confirm it's accessible. |
| 204  | No Content        | ✅ Successful but no data returned. Expected for DELETE or updates. |

---

## 🟡 3xx – Redirection

| Code | Meaning             | Action / Resolution                                        |
|------|---------------------|------------------------------------------------------------|
| 301  | Moved Permanently   | 🔧 Update bookmarks or links. Used for SEO-safe redirects. |
| 302  | Found (Temporary)   | ⚠️ Avoid caching. Used in temporary redirects like login.  |
| 304  | Not Modified        | ✅ Content hasn't changed. Used with caching headers.       |

---

## 🔴 4xx – Client Errors

| Code | Meaning           | Action / Resolution                                                    |
|------|-------------------|------------------------------------------------------------------------|
| 400  | Bad Request       | 🛠️ Fix malformed syntax, headers, or request body.                      |
| 401  | Unauthorized      | 🔑 Check authentication credentials or tokens.                         |
| 403  | Forbidden         | 🔐 Authenticated but not allowed. Review access permissions.           |
| 404  | Not Found         | 🔎 Resource missing. Check endpoint paths or routing configs.          |
| 429  | Too Many Requests | 🕒 Implement retry logic or backoff. Check API rate limits.            |

---

## 🔥 5xx – Server Errors

| Code | Meaning               | Action / Resolution                                                    |
|------|-----------------------|------------------------------------------------------------------------|
| 500  | Internal Server Error | 🧪 Inspect logs. Look for exceptions or broken server logic.            |
| 502  | Bad Gateway           | 🔌 Check reverse proxy or upstream server connection.                  |
| 503  | Service Unavailable   | 🚦 Server overloaded or down. Retry later or monitor system health.    |
| 504  | Gateway Timeout       | ⏱️ Timeout from upstream server. Investigate network or backend lag.   |

---

## 📦 Use Cases

- 🧱 **Developers** – Understand status codes in APIs and frontend/backend integration.
- 🛡️ **Security Engineers** – Monitor for 401/403 issues or rate limiting (429).
- ⚙️ **DevOps/SREs** – Quickly triage 5xx issues in logs or uptime monitors.

---

## 🔗 References

- [MDN Web Docs – HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [RFC 7231 – Hypertext Transfer Protocol (HTTP/1.1)](https://datatracker.ietf.org/doc/html/rfc7231)
- [RFC 6585 – Additional Status Codes (429, etc.)](https://datatracker.ietf.org/doc/html/rfc6585)

---

## 📁 License

MIT License. Use and modify freely.

---

## 🛡️ Looking for the Cybersecurity Version?

Check out the companion guide tailored for penetration testing, incident response, and secure web application design:

🔗 [Cybersecurity HTTP Status Code Guide](https://github.com/cherinejoseph/http-status-codes-for-cybersecurity-it.)

---

## 🙌 Contribute

Found something missing or want to improve the formatting? Feel free to fork this repo and submit a pull request.

