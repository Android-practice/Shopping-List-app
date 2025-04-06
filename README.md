# 🛒 MyShoppingListApp

A simple **shopping list app** built with **Android Jetpack Compose**.  
You can easily **add, edit, and delete** the items you want to manage.

---

## ✨ Features

- ➕ Add item
- ✏️ Edit item
- ❌ Delete item

---

## 📱 Previews

<p align="center">
  <img src="https://github.com/Android-practice/Shopping-List-app/blob/cee3919800c689bc84aff7101f1189b9fabe6d90/images/mainview.png" width="200"/>
  <img src="https://github.com/Android-practice/Shopping-List-app/blob/cee3919800c689bc84aff7101f1189b9fabe6d90/images/additem.png" width="200"/>
  <img src="https://github.com/Android-practice/Shopping-List-app/blob/cee3919800c689bc84aff7101f1189b9fabe6d90/images/addedItem.png" width="200"/>
  <img src="https://github.com/Android-practice/Shopping-List-app/blob/cee3919800c689bc84aff7101f1189b9fabe6d90/images/editItem.png" width="200"/>
</p>

---

## 🧠 New Learning

### 📜 LazyColumn

`LazyColumn` is a part of **Jetpack Compose**, used for efficiently displaying lists.

If you try to load all items at once, it might slow down the app.  
**LazyColumn** only loads and displays the items **currently visible on the screen**.

#### ✅ Features
- Loads only the **items that fit on the screen**
- As the user scrolls, **loads more items on the fly**
- Optimized for **memory and rendering performance**

#### 💡 Example usage

```kotlin
LazyColumn {
    items(listOfItems) { item ->
        /* code to display each item */
    }
}
