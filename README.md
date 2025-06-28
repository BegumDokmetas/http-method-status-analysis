# Web Client-Server Architecture – DevTools Testing

This project demonstrates the use of **browser DevTools** to observe client-server interactions through real-world actions such as login, adding items to cart, or deleting items.

## 🔍 Test Scenarios

| Action | Method | Status Code | Description |
|--------|--------|--------------|-------------|
| Homepage visit | GET | 302 | Redirect |
| Login attempt | POST | 400 | Invalid request |
| View favorites | GET | 200 | Success |
| Add item to cart | POST | 200 | Success |
| Update quantity | PUT | 200 | Success |
| Remove item | DELETE | 200 | Success |
| Confirm cart | POST | 428 | Precondition required |

## 🛠 Tools Used

- Chrome DevTools
- Manual Testing
  

## 📄 File

- `Client_Server_HTTP_Method_Analysis.pdf`

## 👩‍💻 Author

Begüm Dökmetaş – QA Trainee
