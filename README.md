# 🚀 **How to Use HTTP Status Code Badges in Markdown**

HTTP status badges provide a clear and visual way to document API responses in your README files or API documentation. With **Shields.io**, you can easily generate badges for various HTTP status codes.

---

## 📚 **What are HTTP Status Code Badges?**

HTTP status code badges display API response statuses in an easy-to-understand visual format. These badges are categorized based on their semantics:

- 🟢 **2xx (Success):** Indicates that the API request was successfully received, understood, and accepted.
- 🔴 **4xx (Client Error):** Indicates a problem with the request sent by the client.
- ⚠️ **5xx (Server Error):** Indicates an issue on the server side.

Using badges for these statuses helps users quickly understand the behavior of your API endpoints.

---

## 🛠️ **How to Create HTTP Status Badges**

You can use the following badge patterns:

- ✅ **Success (200 OK)**
  ```markdown
  ![200 OK](https://img.shields.io/badge/200-OK-brightgreen?labelColor=brightgreen&color=lightgrey)
  ```
  **Preview:**
  ![200 OK](https://img.shields.io/badge/200-OK-brightgreen?labelColor=brightgreen&color=lightgrey)

- ❌ **Client Error (404 Not Found)**
  ```markdown
  ![404 Not Found](https://img.shields.io/badge/404-Not%20Found-red?labelColor=red&color=lightgrey)
  ```
  **Preview:**
  ![404 Not Found](https://img.shields.io/badge/404-Not%20Found-red?labelColor=red&color=lightgrey)

- ⚠️ **Server Error (500 Internal Server Error)**
  ```markdown
  ![500 Internal Server Error](https://img.shields.io/badge/500-Internal%20Server%20Error-yellow?labelColor=yellow&color=lightgrey)
  ```
  **Preview:**
  ![500 Internal Server Error](https://img.shields.io/badge/500-Internal%20Server%20Error-yellow?labelColor=yellow&color=lightgrey)

---

## 🎯 **How to Use Badges in API Documentation**

You can integrate these badges directly into your API documentation to represent response statuses for each endpoint:

```markdown
### GET /api/users

**Description:** Fetches the list of users.

**Success Response:**
![200 OK](https://img.shields.io/badge/200-OK-brightgreen?labelColor=brightgreen&color=lightgrey)

**Client Error Response:**
![404 Not Found](https://img.shields.io/badge/404-Not%20Found-red?labelColor=red&color=lightgrey)

**Server Error Response:**
![500 Internal Server Error](https://img.shields.io/badge/500-Internal%20Server%20Error-yellow?labelColor=yellow&color=lightgrey)
```

### **Rendered Example:**

**Success Response:**
![200 OK](https://img.shields.io/badge/200-OK-brightgreen?labelColor=brightgreen&color=lightgrey)

**Client Error Response:**
![404 Not Found](https://img.shields.io/badge/404-Not%20Found-red?labelColor=red&color=lightgrey)

**Server Error Response:**
![500 Internal Server Error](https://img.shields.io/badge/500-Internal%20Server%20Error-yellow?labelColor=yellow&color=lightgrey)

---

## 🧠 **Customization Tips**

- `labelColor`: Controls the background color of the **status code** section.
- `color`: Controls the background color of the **description/message** section.
- `style`: Options include `flat`, `plastic`, or `for-the-badge`.

Example with style:
```markdown
![200 OK](https://img.shields.io/badge/200-OK-brightgreen?style=for-the-badge)
```
**Preview:**
![200 OK](https://img.shields.io/badge/200-OK-brightgreen?style=for-the-badge)

---

## 🔗 **Useful Links**

- [Shields.io Badge Generator](https://shields.io/)
- [HTTP Status Codes - MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [Custom Badge Generator](https://markdown-badge-generator.streamlit.app/)

---
