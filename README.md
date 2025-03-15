# BottomSheetFragment Implementation in Android

## 📌 What is a Bottom Sheet?
A **Bottom Sheet** is a sliding panel that appears from the bottom of the screen. It is used to display additional content, options, or actions without interrupting the user’s current screen.

Android provides two types of bottom sheets:
- **Modal Bottom Sheet** – Appears as a dialog and can be dismissed.
- **Persistent Bottom Sheet** – Remains visible and can expand or collapse.

This guide focuses on implementing a **Modal Bottom Sheet** using `BottomSheetDialogFragment`.

---

## 🚀 How to Implement a Modal Bottom Sheet

### **Step 1: Add Dependencies**
Ensure you have the Material Components library in your `build.gradle` (Module-level):
```gradle
dependencies {
    implementation 'com.google.android.material:material:1.9.0'
}
```

---

### **Step 2: Create the Bottom Sheet Layout**
Create a new XML layout file for the bottom sheet UI.

---

### **Step 3: Create `BottomSheetFragment` Class**
Define a `BottomSheetDialogFragment` subclass to handle the bottom sheet UI and behavior.

---

### **Step 4: Show the Bottom Sheet from an Activity**
Trigger the bottom sheet from main activity.

---

### **Step 5: Add a Button in `activity_main.xml` to Show the Bottom Sheet**

---

## 🎯 Summary
- **`BottomSheetFragment`** extends `BottomSheetDialogFragment` to create a modal bottom sheet.
- Use **`show(getSupportFragmentManager(), tag)`** to display the bottom sheet.
- Customizable UI can be built using an XML layout.
- Enhances user experience by providing additional UI interactions without switching screens.

## How to View the Animations
Below is the demo video:

<a href="https://github.com/user-attachments/assets/6a939fe8-52d2-470b-96ed-d2bdbfda8c40"
  alt="Watch the video">
</a>

