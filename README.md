
```
eCommerce
└─ Full_3_1team
   ├─ README.md
   ├─ backend
   │  ├─ .env
   │  ├─ config
   │  │  └─ dbConfig.ts
   │  ├─ dist
   │  │  └─ server.js
   │  ├─ feature
   │  │  ├─ auth
   │  │  │  ├─ controller
   │  │  │  │  └─ AuthController.ts
   │  │  │  ├─ domains
   │  │  │  │  └─ Auth.ts
   │  │  │  ├─ repo
   │  │  │  │  └─ AuthRepo.ts
   │  │  │  └─ services
   │  │  │     └─ AuthService.ts
   │  │  ├─ cart
   │  │  │  ├─ controller
   │  │  │  │  └─ CartController.ts
   │  │  │  ├─ domains
   │  │  │  │  └─ Cart.ts
   │  │  │  ├─ repo
   │  │  │  │  └─ CartRepo.ts
   │  │  │  └─ services
   │  │  │     └─ CartService.ts
   │  │  ├─ orders
   │  │  │  ├─ controller
   │  │  │  │  └─ OrderController.ts
   │  │  │  ├─ domains
   │  │  │  │  └─ Orders.ts
   │  │  │  ├─ repo
   │  │  │  │  └─ OrderRepo.ts
   │  │  │  └─ services
   │  │  │     └─ OrderService.ts
   │  │  ├─ payments
   │  │  │  ├─ controller
   │  │  │  │  └─ PaymentsController.ts
   │  │  │  ├─ domains
   │  │  │  │  └─ Payments.ts
   │  │  │  ├─ repo
   │  │  │  │  └─ PaymentsRepo.ts
   │  │  │  └─ services
   │  │  │     └─ PaymentsrService.ts
   │  │  ├─ product
   │  │  │  ├─ controller
   │  │  │  │  └─ ProductController.ts
   │  │  │  ├─ domains
   │  │  │  │  └─ Product.ts
   │  │  │  ├─ repo
   │  │  │  │  └─ ProductRepo.ts
   │  │  │  └─ services
   │  │  │     └─ ProductService.ts
   │  │  └─ user
   │  │     ├─ controller
   │  │     │  └─ UserController.ts
   │  │     ├─ domains
   │  │     │  └─ User.ts
   │  │     ├─ repo
   │  │     │  └─ UserRepo.ts
   │  │     └─ services
   │  │        └─ UserService.ts
   │  ├─ middlewares
   │  │  └─ AuthMiddleware.ts
   │  ├─ package-lock.json
   │  ├─ package.json
   │  ├─ routes
   │  │  ├─ AuthRoutes.ts
   │  │  ├─ CartRoutes.ts
   │  │  ├─ OrderRoutes.ts
   │  │  ├─ PaymentsRoutes.ts
   │  │  └─ ProductRoutes.ts
   │  ├─ server.ts
   │  └─ tsconfig.json
   └─ frontend
      ├─ .env
      ├─ eslint.config.js
      ├─ index.html
      ├─ package-lock.json
      ├─ package.json
      ├─ public
      │  └─ vite.svg
      ├─ src
      │  ├─ app
      │  │  ├─ App.css
      │  │  └─ App.tsx
      │  ├─ assets
      │  │  └─ react.svg
      │  ├─ entities
      │  │  ├─ auth.ts
      │  │  ├─ cart.ts
      │  │  ├─ order.ts
      │  │  ├─ payments.ts
      │  │  └─ product.ts
      │  ├─ features
      │  │  ├─ auth
      │  │  │  ├─ api
      │  │  │  │  └─ Auth.ts
      │  │  │  ├─ model
      │  │  │  │  └─ AuthModel.ts
      │  │  │  └─ ui
      │  │  │     └─ Login.tsx
      │  │  ├─ cart
      │  │  │  ├─ api
      │  │  │  │  └─ Cart.ts
      │  │  │  ├─ model
      │  │  │  │  └─ CartModel.ts
      │  │  │  └─ ui
      │  │  │     └─ Cart.tsx
      │  │  ├─ order
      │  │  │  ├─ api
      │  │  │  │  └─ Order.ts
      │  │  │  ├─ model
      │  │  │  │  └─ OrderModel.ts
      │  │  │  └─ ui
      │  │  │     └─ Order.tsx
      │  │  ├─ payments
      │  │  │  ├─ api
      │  │  │  │  └─ Payments.ts
      │  │  │  ├─ model
      │  │  │  │  └─ PaymentsModel.ts
      │  │  │  └─ ui
      │  │  │     └─ Payments.tsx
      │  │  ├─ product
      │  │  │  ├─ api
      │  │  │  │  └─ Product.ts
      │  │  │  ├─ model
      │  │  │  │  └─ ProductModel.ts
      │  │  │  ├─ product-form
      │  │  │  │  ├─ api
      │  │  │  │  │  ├─ CreateProduct.ts
      │  │  │  │  │  └─ EditProduct.ts
      │  │  │  │  ├─ model
      │  │  │  │  │  └─ ProductFormModel.ts
      │  │  │  │  └─ ui
      │  │  │  │     └─ ProductForm.tsx
      │  │  │  └─ ui
      │  │  │     └─ Product.tsx
      │  │  ├─ review
      │  │  │  ├─ api
      │  │  │  ├─ model
      │  │  │  └─ ui
      │  │  └─ summary
      │  │     ├─ api
      │  │     ├─ model
      │  │     └─ ui
      │  ├─ index.css
      │  ├─ main.tsx
      │  ├─ pages
      │  │  ├─ DashBoard.tsx
      │  │  ├─ cart
      │  │  │  └─ Cart.tsx
      │  │  ├─ home
      │  │  │  ├─ MainPage.tsx
      │  │  │  ├─ TestPage.css
      │  │  │  └─ TestPage.tsx
      │  │  ├─ login
      │  │  │  ├─ Login.tsx
      │  │  │  └─ Signup.tsx
      │  │  ├─ order
      │  │  │  ├─ Order.tsx
      │  │  │  ├─ OrderBoard.tsx
      │  │  │  └─ OrderDetail.tsx
      │  │  ├─ payments
      │  │  │  └─ Payments.tsx
      │  │  ├─ product
      │  │  │  ├─ ProductBoard.tsx
      │  │  │  ├─ ProductCreate.tsx
      │  │  │  ├─ ProductDetail.tsx
      │  │  │  ├─ ProductEdit.tsx
      │  │  │  ├─ ProductList.tsx
      │  │  │  └─ WishList.tsx
      │  │  ├─ profile
      │  │  │  └─ MyPage.tsx
      │  │  └─ review
      │  │     └─ Review.tsx
      │  ├─ shared
      │  │  ├─ axios
      │  │  │  └─ axios.ts
      │  │  ├─ style
      │  │  │  └─ button.css
      │  │  ├─ types
      │  │  │  └─ ProductType.ts
      │  │  ├─ ui
      │  │  │  └─ button.tsx
      │  │  └─ utils
      │  │     └─ utils.ts
      │  ├─ vite-env.d.ts
      │  └─ widgets
      │     ├─ footer
      │     │  ├─ Footer.css
      │     │  └─ Footer.tsx
      │     ├─ header
      │     │  ├─ Header.css
      │     │  └─ Header.tsx
      │     ├─ product-card
      │     │  ├─ ProductCard.css
      │     │  └─ ProductCard.tsx
      │     └─ slider
      │        ├─ Slider.css
      │        └─ Slider.tsx
      ├─ tsconfig.app.json
      ├─ tsconfig.json
      ├─ tsconfig.node.json
      └─ vite.config.ts

```