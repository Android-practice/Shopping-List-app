# 🛒 MyShoppingListApp

## 📜 LazyColumn

`LazyColumn` is a part of **Jetpack Compose**, used for efficiently displaying lists.  
If you try to load all items at once, it might slow down the app.  
**LazyColumn only loads and displays the items currently visible on the screen.**

### ✅ Features
- Loads only the **items that fit on the screen**
- As the user scrolls, **loads more items on-the-go**
- Optimized for memory and rendering performance

### 💡 Example usage
```kotlin
LazyColumn {
    items(listOfItems) { item ->
        /* code to display each item */
    }
}


