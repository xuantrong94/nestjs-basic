project-root/
│
├── src/
│ ├── main.ts # Điểm khởi đầu của ứng dụng
│ ├── app.module.ts # Module gốc của ứng dụng
│ ├── app.controller.ts # Controller chính (nếu cần)
│ ├── app.service.ts # Service chính (nếu cần)
│ │
│ ├── config/ # Cấu hình ứng dụng
│ │ ├── configuration.ts # Cấu hình chung
│ │ └── validation.schema.ts # Schema validation cho env
│ │
│ ├── modules/ # Các module của ứng dụng
│ │ ├── users/
│ │ │ ├── users.module.ts
│ │ │ ├── users.controller.ts
│ │ │ ├── users.service.ts
│ │ │ ├── dto/
│ │ │ ├── entities/
│ │ │ └── interfaces/
│ │ │
│ │ ├── auth/
│ │ │ ├── auth.module.ts
│ │ │ ├── auth.controller.ts
│ │ │ ├── auth.service.ts
│ │ │ └── strategies/
│ │ │
│ │ └── ... (các module khác)
│ │
│ ├── common/ # Các thành phần dùng chung
│ │ ├── decorators/
│ │ ├── filters/
│ │ ├── guards/
│ │ ├── interceptors/
│ │ ├── middlewares/
│ │ └── pipes/
│ │
│ └── shared/ # Các utility và helper functions
│ ├── utils/
│ └── constants/
│
├── test/ # Thư mục chứa các file test
│ ├── unit/
│ └── e2e/
│
├── dist/ # Thư mục build (sẽ được tạo sau khi build)
│
├── node_modules/ # Thư mục dependencies
│
├── .env # File chứa biến môi trường
├── .env.example # File mẫu cho .env
├── .gitignore
├── nest-cli.json
├── package.json
├── tsconfig.json
└── README.md
