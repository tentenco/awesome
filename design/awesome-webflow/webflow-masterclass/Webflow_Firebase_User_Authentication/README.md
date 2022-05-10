# Webflow + Firebase用戶認證

你可以在https://webflow-authentication.webflow.io/sign-up 找到一個Demo。

## 1. 設置Firebase認證

登錄到Firebase控制台。創建一個新的應用 程式，從左邊的菜單，在``開發'``下，導航到``認證'``。啟用``電子信箱/密碼'``登錄提供者。之後，在當前的Firebase項目下創建一個Web應用 程式，並複製給定的firebaseConfig對象。

## 2. 創建Webflow頁面

進入項目設置和```自定義程式碼```標籤。將``webflow-custom-code-before-body.html``gist文件中的內容添加到``Footer Code``輸入中。將``webflowAuth.firebaseConfig``替換為你在上一步複製的內容。之後，進入設計器，創建3個新頁面。

  1. ``/user````頁面，用於登錄的用戶。
  2. 2. ``/log-in``頁面，用於登錄。
  3. 3. ``/sign-up``頁面，用於註冊。
  
在``/sign-up``頁面，創建一個表單，在裡面添加一個提交按鈕和兩個輸入欄位--電子信箱和密碼。然後做以下調整。

  1. 給予表單元素（表單內的表單元素，表單>表單）自定義數據屬性，稱為`data-signup-form`。
  2. 2.給電子信箱欄位自定義數據屬性，稱為 "data-signup-email"。
  3. 3. 給予密碼欄位自定義數據屬性，稱為`data-signup-password'。
  4. 4. 給予表單錯誤元素自定義數據屬性，稱為`data-signup-error'。
  5. 5.在body元素中添加自定義數據屬性，稱為`data-user-unauth`。
  
在``/log-in``頁面，創建一個表單，在裡面添加一個提交按鈕和兩個輸入欄位--電子信箱和密碼。然後做以下調整。

  1. 給予表單元素（表單內的表單元素，表單>表單）自定義數據屬性，稱為`data-login-form`。
  2. 2.給電子信箱欄位自定義數據屬性，稱為`data-login-email'。
  3. 3. 給予密碼欄位自定義數據屬性，稱為 "data-login-password"。
  4. 4. 給予表單錯誤元素自定義數據屬性，稱為 "data-login-error"。
  5. 5. 在body元素中添加自定義數據屬性，稱為`data-user-unauth`。
  
在``/user``頁面中，在body元素中添加自定義數據屬性，稱為`data-user-auth`。除此之外，你可以通過給元素添加自定義數據屬性`data-user`來顯示從Firebase返回的任何用戶屬性。在這之後，你可以使用帶有大括弧的用戶屬性，例如：``你的電子信箱是{{email}}``。

如果你有一個導航元素，你可以從那裡導航到``/登錄``，``/註冊``等頁面，你可以通過使用自定義數據屬性``data-user-auth`和``data-user-unauth`來調整其可見性。你也可以將這些數據屬性中的任何一個添加到body元素中，這將調整指定頁面的可見性。註銷按鈕可以通過給連結元素一個自定義數據屬性`data-logout`來創建。

## 3. 貢獻

一些想法取自Jason Dark的YouTube影片系列，你可以在https://www.youtube.com/watch?v=30AIpEnsEaQ&list=PL4TuDUnZkkhzSwfbFj6EJjxim6218ORc0。