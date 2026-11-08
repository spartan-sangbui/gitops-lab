# gitops-lab

Repo thực hành Lab 03 (GitOps với Argo CD) - mô phỏng repo `infra-argocd` của team.

- Thư mục `apps/` chứa các Argo CD `Application` (mỗi file một app) mà root app theo dõi.
- Trạng thái ban đầu: chưa có `apps/`. Lab sẽ tạo `apps/values-demo.yaml`.
- Không chứa secret. Cluster chỉ là `kind` chạy local.
