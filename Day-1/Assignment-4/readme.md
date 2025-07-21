## 🛠️ Corrections Made to the HTML Form

| **Original Error**                            | **Correction**            | **Why?**                                                                |
| --------------------------------------------- | -------------------------- | ----------------------------------------------------------------------- |
| `<label Name="username">`                     | `<label for="username">`    | `<label>` doesn't support `Name`. `for` connects to the related `input` `id`. |
| `name="username>`                              | `name="username"`           | Missing closing `"` caused invalid attribute syntax.                    |
| `<input typ="password"`                       | `<input type="password">`   | `type` was misspelled as `typ`.                                         |
| `<button Submit>`                             | `<button type="submit">`    | `<button>` doesn't accept `Submit` like that; `type="submit"` is correct. |
| `<buttn>`                                     | `<button>`                  | Tag name was misspelled.                                                |
| Missing closing tags on inputs (self-closing) | `<input ... >`              | Inputs should be properly closed.                                       |

---

These corrections ensure the form is valid, functional, and follows standard HTML best practices.
