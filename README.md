# Google Search Clone (CS50W Project 0)

A front-end implementation of Google Search, Google Image Search, and Google Advanced Search. This project focuses on replicating Google's aesthetics and functionality.

## 💡 Features

### 1. Main Search Page
* **Standard Search:** Redirects users to Google's search results using the `q` parameter.
* **I'm Feeling Lucky:** Implements the `btnI` parameter to take users directly to the first search result.
* **AI Mode:** Utilises the `udm=50` parameter to access Google's AI-integrated search results layout.

### 2. Image Search
* Allows users to search specifically for images using the `udm=2` parameter.

### 3. Advanced Search
* **Grid Layout:** Built with a precise 2-column **CSS Grid** to align labels and input fields perfectly.
* Supports four core search filters:
    * All these words (`as_q`)
    * This exact word or phrase (`as_epq`)
    * Any of these words (`as_oq`)
    * None of these words (`as_eq`)

## 🛠️ Technical Breakdown

### CSS Architecture
* **Flexbox & Grid:** Used `display: flex` for main page centering and `display: grid` for the Advanced Search form.
* **Modern Gradient Borders:** The "AI Mode" button features a sophisticated gradient border achieved through `background-clip` and `background-origin`.
* **State Management:** Custom CSS for `:hover` and `:focus` states to provide immediate visual feedback.
* **Autofill Fix:** Includes a `-webkit-autofill` override to maintain the integrity of the design of this website.
