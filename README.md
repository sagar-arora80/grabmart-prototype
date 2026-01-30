# GrabMart Out-of-Stock (OOS) Experience Prototype

This repository houses a high-fidelity, mobile-first web prototype designed to reimagine and enhance the **Out-of-Stock (OOS) handling experience** for GrabMart users. 

**Live Demo:** [https://sagar-arora80.github.io/grabmart-prototype/](https://sagar-arora80.github.io/grabmart-prototype/)

## 🎯 Context & Objective
When users shop for groceries online, encountering out-of-stock items is a major friction point that leads to:
1.  **Cart Abandonment**: Users leave if key ingredients are missing.
2.  **Reduced Basket Size**: Users delete unavailable items without finding replacements.
3.  **Frustration**: Poor communication of availability or irrelevant substitutes.

**The Goal**: To create a seamless, proactive, and "zero-dead-end" experience where users are guided to relevant alternatives *instantly*, without disrupting their shopping flow.

## 🚀 Key Solution Features

### 1. Proactive Inline Substitution
Instead of hiding substitutes in a separate menu or contacting the user post-checkout, this prototype surfaces **"Best Alternatives" directly in the feed**.
*   **Zero-Click Discovery**: Substitutes appear inline immediately when an item is OOS.
*   **Visual Logic**: OOS items are de-emphasized (grayscale/opacity), while substitutes are highlighted (green/accent borders).

### 2. Global Quantity Controls
We upgraded the interaction model across the entire app.
*   **"Add" to "Adjust"**: The simple `(+)` button transforms into a full **Quantity Control** `[-] 1 [+]` upon interaction.
*   **Ease of Removal**: Users can decrement or remove items directly from the Product Card (Home, Search, Category) without visiting the Cart.

### 3. Smart Search & Category Handling
*   **Search**: If a searched item is OOS, the result is still shown (to confirm we understood the query) but immediately offers an "Available Alternative" block.
*   **Category**: Duplicate detection ensures the layout remains clean while still offering swaps for missing goods.

### 4. Cart Recovery Flow
*   **OOS in Cart**: If an item goes OOS while in the cart, it doesn't just disappear. It flags the issue and offers a "Best Match" replacement right next to the removed item.
*   **Sticky Footer**: A clear "Place Order" CTA ensures users can always proceed.

## 📱 User Journeys

The prototype covers 4 core discovery loops:

1.  **Home Feed**: Browsing top recommendations and handling OOS items in the main feed.
2.  **Search**: Searching for specific items (e.g., "milk", "bread") and managing OOS results.
3.  **Category Listing**: Browsing specific aisles (e.g., Bakery) with smart OOS swaps.
4.  **Product Detail Page (PDP)**: A dedicated page for items, offering "Add Closest Alternative" when the main SKU is unavailable.

## 🛠 Tech Stack
*   **Frontend**: React (Vite)
*   **Styling**: TailwindCSS (Custom design system for typography/colors)
*   **Routing**: React Router DOM (Single Page Application)
*   **Icons**: Lucide React
*   **Deployment**: GitHub Pages

## 🏃‍♂️ How to Run Locally

1.  Clone the repository:
    ```bash
    git clone https://github.com/sagar-arora80/grabmart-prototype.git
    ```
2.  Install dependencies:
    ```bash
    cd grabmart-prototype
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

## 📸 Screenshots

*(Refer to the Live Demo to see the interactive prototype in action)*
