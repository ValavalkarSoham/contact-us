
---

## 🧩 Features

- Input fields: **Name**, **Email**, and **Message**
- Client-side validation using **JavaScript**
- **Regex-based** email format validation
- Clear **error messages** shown below inputs
- Prevents form submission if inputs are invalid
- Shows **success message** when all fields are valid
- Styled with basic, responsive **CSS**

---

## 🧪 Validation Rules

| Field     | Validation Rule                                      |
|-----------|-------------------------------------------------------|
| Name      | Must not be empty                                     |
| Email     | Must not be empty and match email regex format        |
| Message   | Must not be empty                                     |

**Regex Used for Email Validation:**
```js
/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/
