# Yêu cầu

- Cấu hình hệ thống phân quyền dựa trên RBAC có thể tùy chỉnh (Mẫu data cho phân quyền trong BE cho 1 CRM)
- Có thể cấu hình cho user có thể truy cập vào các menu (FE menu), action (FE action như button) và api theo endpoint
- Gợi ý giúp tôi theo các mẫu dự án thực tế

# Tech stack

- BE: NestJS + TypeORM + Postgres (các entity relation theo field thôi không cần các decorator relation)
- FE: React + TypeScript + Antd với mẫu khi tạo 1 resource và gán cho role thì các button và action của resource sẽ được gán cho role

# Thêm

- Viết ngắn gọn và mô tả luồng logic của hệ thống phân quyền
- Ví dụ về 1 data example khi thêm 1 resource thực tế
