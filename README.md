# Nigeria States and LGAs Data

A comprehensive, ready-to-use JSON dataset containing all **36 Nigerian States** and the **Federal Capital Territory (FCT)**, along with their respective **Local Government Areas (LGAs)**.

## 📋 Table of Contents

- [Features](#features)
- [Data Structure](#data-structure)
- [Contribution](#contribution)

---

## ✨ Features

- **Lightweight:** Pure JSON format with no external dependencies.
- **Accurate:** Includes all 774 Local Government Areas.
- **Formatted:** Clean, indented, and alphabetically sorted states for easy lookups.
- **Developer Friendly:** Ideal for populating dropdown menus, form validations, or database seeding.

---

## 🏗 Data Structure

The data is structured as a single object where the **keys** are the state names and the **values** are arrays of strings containing the LGAs.

```json
{
  "State Name": [
    "LGA 1",
    "LGA 2",
    "LGA 3"
  ]
}
```

---


## 🤝 Contribution

Found a typo or a missing LGA? Contributions are welcome!

1. Fork the project.
2. Create your feature branch:

   ```bash
   git checkout -b feature/FixLGA
   ```

3. Commit your changes:

   ```bash
   git commit -m "Fixed typo in Kano LGA"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/FixLGA
   ```

5. Open a Pull Request.

---

## 📜 License

This data is provided under the MIT License. Feel free to use it in any personal or commercial project.
